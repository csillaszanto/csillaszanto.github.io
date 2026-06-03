---
layout: base
title:  "Finding the Right Swarm — in Life and in Data"
description: "What a Beeswarm Chart Can Teach Us"
date:   2025-10-05 12:00:00 +0100
tags: beeswarm chart-types
categories: data visualization
comments: false
---

![Illustration image](/assets/images/chart-types/pexels-michael.jpg "Foto: Michael, Pexels")

# Finding the Right Swarm — in Life and in Data

## What a Beeswarm Chart Can Teach Us

{% for tag in page.tags %}
<code>#{{ tag }}</code>{% endfor %}

<br/>

Marmot was a senior software developer in a team of a dozen animals.

He worked precisely and reliably, always balancing user needs with what could realistically be built. Yet he often felt out of place - different in color, rhythm, and values.

At the office, small talk drained him. Some colleagues ignored his greetings entirely. One day, he noticed a young intern doing absolutely nothing: scrolling through videos, sleeping at his desk. Marmot couldn't decide whether it was laziness or provocation, but it frustrated him.

He thought about the **Dunning–Kruger effect**: how people with limited knowledge often overestimate their abilities, while those with deep expertise are more aware of what they *don't* know. The office seemed full of misplaced confidence and invisible competence.

But over time, Marmot realized something.

The problem wasn't only the individuals around him. It was the *swarm* he was in.

He needed a place where people were seen for who they were, not blurred into averages. So he started attending conferences, joining communities, and contributing to side projects.

Eventually, he found joy again in *choosing his swarm*.

<br/>

## What This Has to Do With Data Visualization

Many charts focus on summaries.

Bar charts, histograms, and box plots help us understand distributions, but they hide the individual items that create those patterns. We see aggregates, not people. Averages, not stories.

A **beeswarm chart** takes a different approach.

Instead of grouping data into bins, it displays every observation as a circle positioned along an axis - such as salary or age. The circles "swarm" around the axis, staying close enough to reveal density while avoiding overlap.

The result:

* You see both the *overall distribution* and the *individual values*.
* Clusters and outliers become immediately visible.
* Color can represent categories.
* Circle size can encode magnitude.
* Interactive versions can reveal exact values through tooltips or zooming.

Beeswarm charts are especially useful when you want to show how values are distributed without reducing them to averages. They're a great choice for visualizing developer salaries, rankings, survey responses, or any dataset where individual observations matter.

If you'd like to build one yourself, **D3.js** is a popular option. The core idea is simple: keep circles as close as possible while ensuring they don't overlap. [Nathan Yau provides an excellent example](https://flowingdata.com/2025/09/09/salary-and-occupation-2024/ "Nathan Yau provides an excellent example")  in his salary and occupation visualization.

<br/>

## Seeing Individuals, Not Averages

Marmot eventually built his own business - his own swarm - carefully choosing who to collaborate with.

Like a good beeswarm chart, his new team made each individual visible while still revealing a larger pattern that made sense.

The next time you visualize a dataset, ask yourself:

Do you want to show the average bar?

Or the living swarm that tells the real story?

{%- include ebook.html -%}
