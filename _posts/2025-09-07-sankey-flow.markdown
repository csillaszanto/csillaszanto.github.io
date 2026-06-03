---
layout: base
title:  "Are Your Flows Being Wasted Like Jaguar’s?"
description: "What a Frustrated Developer Taught Me About Sankey Diagrams"
date:   2025-09-07 12:00:00 +0100
tags: sankey chart-types
categories: data visualization
comments: false
---

![Illustration image](/assets/images/chart-types/sankey.png "Source: https://observablehq.com/@d3/sankey-component")

<small>(Picture taken from Observable site (https://observablehq.com/@d3/sankey-component))</small>

# Are Your Flows Being Wasted Like Jaguar’s?

## What a Frustrated Developer Taught Me About Sankey Diagrams

{% for tag in page.tags %}
<code>#{{ tag }}</code>{% endfor %}

<br/>

Not long ago, I was working with a company where I met a developer I'll call Jaguar.

Jaguar was one of the most capable developers on the team. Sharp, fast, and highly effective, he thrived on solving problems, delivering quality work, and moving projects forward.

But the reality of his work looked very different.

He was shuffled between projects like an interchangeable resource. He had little influence over architectural decisions. And his most productive hours disappeared into meetings, alignment sessions, and corporate rituals that never touched the real problems.

As I listened to him describe his frustration, something dawned on me.

If we could visualize Jaguar's workday, it would look exactly like a **Sankey diagram**.

Imagine him starting each morning with a thick stream of energy and focus. As the day progresses, that stream splits into smaller and smaller branches: meetings, status updates, approvals, politics, and context switching. By the end, only a thin stream reaches the work where he creates the most value.

That's exactly what a Sankey diagram is designed to show.

<br/>

## What Is a Sankey Diagram?

A Sankey diagram is a **flow diagram** that emphasizes how something moves from one state to another.

The defining characteristic is that the width of each flow is proportional to the quantity it represents.

* Thick lines represent larger volumes.
* As flows split, the branches become thinner, showing how much is being divided or lost.
* The result often resembles a river system breaking into smaller tributaries.

What makes Sankey diagrams so powerful is that they don't just show totals. They show where things go, how they break apart, and where value is lost along the way.

<br/>

## A Brief History

The roots of the Sankey diagram go back to the nineteenth century.

One of the earliest examples was Charles Minard's legendary visualization of Napoleon's disastrous march into Russia, where the width of the line represented the shrinking size of the army.

Later, Captain Matthew Henry Phineas Riall Sankey of the Royal Engineers used similar diagrams to illustrate energy efficiency in steam engines. His work became so influential that the chart type eventually took his name.

<br/>

## Where Are Sankey Diagrams Useful?

Sankey diagrams are particularly effective whenever you want to understand how resources flow through a system.

Some common applications include:

### Energy and Sustainability

Visualizing how input energy flows through a system and how much is lost as waste heat.

### Finance

Showing how revenue, costs, or budgets split into different categories and where money leaks away.

### Operations and Processes

Tracking how people's time, effort, or tasks are distributed between productive and non-productive activities.

### Data Categorization

Showing how large groups break down into subgroups, such as customers moving into segments and then into different outcomes.

A close relative of the Sankey diagram is the **alluvial diagram**. While Sankey diagrams focus on continuous flows and branching, alluvial diagrams emphasize how entities move between categories over time.

<br/>

## When Should You Use a Sankey Diagram?

Sankey diagrams are not a basic chart type, and that’s part of their power - and also their risk.

The risk is that some audiences may not immediately understand how to read them. If you choose a Sankey diagram, you need to guide viewers through the story.

The upside is that few visualizations reveal inefficiencies as clearly.

Two rules help keep them effective:

1. Use a Sankey diagram only when it provides more clarity than a simpler chart.
2. Test it with your audience. Does it help them answer their real questions? Does it make the flow easier to understand? If not, refine it.

A Sankey diagram should never exist because it looks interesting. It should exist because it reveals something important.

If you'd like to create one yourself, tools such as [SankeyMATIC](https://sankeymatic.com/), Flourish, d3.js, and Tableau make the process relatively straightforward.

<br/>

## The Lesson from Jaguar

After our conversation, Jaguar admitted he felt like he was pouring his energy into a broken system - one where most of his effort disappeared into useless branches.

And I think that's a lesson for all of us.

If you drew a Sankey diagram of your own time and energy:

* Where would your main stream of value be?
* Where does it branch into activities that genuinely matter?
* Where does it leak into things that don't move you forward?

The hidden power of a Sankey diagram is that once flows become visible, they become manageable.

You can close unnecessary branches. You can simplify. You can redirect your energy toward the outcomes that matter most.

Jaguar eventually realized he couldn't keep wasting his flow that way.

Perhaps the better question is whether you can.

So take a moment and map your own flow - even if only in your head.

How much of your energy is actually going where you want it to go?

{%- include ebook.html -%}
