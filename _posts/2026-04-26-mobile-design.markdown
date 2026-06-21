---
layout: base
title:  "Understanding Needs Space"
description: "Developing Visualizations for Mobile Devices"
date:   2026-04-26 12:00:00 +0100
tags: mobile design
categories: data visualization
comments: false
---

![Illustration image](/assets/images/arch-design/pexels-pixabay.jpg "Foto: Pixabay, Pexels")

# Understanding Needs Space

## Developing Visualizations for Mobile Devices

{% for tag in page.tags %}
<code>#{{ tag }}</code>{% endfor %}

<br/>

A couple of days ago, I was sitting on a train when a woman took the seat opposite me.

She pulled a brand-new book out of her bag and, before opening it, turned it over to read the back cover. You could almost see the curiosity building. She didn't know the story yet, but she was already stepping into it.

Then she began reading.

Page after page, she disappeared into the book. Completely focused. No distractions, no glances at her phone, no awareness of the noise around her. Just her and the text.

What stayed with me wasn't simply that she was reading. It was how much **space** she had.

Space to imagine.

Space to interpret.

Space to build her own version of the story.

Everyone else around her was on their phones, scrolling through fragments of content that barely demand attention. Fast, superficial, and strangely empty.

She was doing the opposite.

Fully present. Fully absorbed.

That contrast stayed with me, and later I found myself thinking about it in a completely different context: data visualization.

In web development, we're used to thinking mobile first. For text-heavy content, it works well. Content stacks naturally, layouts become simpler, and everything remains accessible on smaller screens.

But visualizations are different.

A chart isn't just content. It's structure. Relationships, distances, proportions, every element carries meaning. And that meaning depends heavily on space.

When we take a visualization designed for a larger screen and squeeze it into a mobile layout, something subtle but important happens:

We take away its space.

Labels become cramped. Elements overlap. Proportions get harder to judge. Patterns become more difficult to see.

And just like that, we don't merely make the chart smaller, but we make it harder to interpret.

In a sense, we do the opposite of what that book allowed.

Instead of creating room for understanding, we constrain it.

Designing mobile first doesn't automatically solve the problem either. Scaling a chart up can create a different set of issues. Elements that worked in close proximity suddenly feel disconnected. Balance changes. What looked clear on a phone can feel awkward on a larger screen.

Unlike text, visualizations don't naturally adapt by stacking or stretching.

They need to be rethought.

A good mobile visualization is often a **different visualization**, not just a resized version.

For smaller screens, that might mean:

* Moving legends and labels above or below the chart instead of beside it.
* Reducing or simplifying elements while preserving readability.
* Choosing a completely different chart type.

For example, instead of a scatterplot or beeswarm plot with many overlapping dots, short vertical lines with slight transparency can sometimes work better. Overlap creates darker areas, revealing density and making patterns easier to see in limited space.

Same data. Different design. Better interpretation.

The idea is simple:

Understanding needs space.

And when space is limited, design has to adapt, not compress.

Just as that woman on the train had the right conditions to immerse herself in a book, users need the right conditions to make sense of visualizations.

Take away that space, and you don't just make things smaller.

You make them harder to understand.

{%- include ebook.html -%}
