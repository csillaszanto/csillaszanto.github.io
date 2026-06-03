---
layout: base
title:  "Seeing Relationships: Why Graphs Matter in AI and Beyond"
description: "Graphs &  Networks in the Age of AI"
date:   2025-09-21 12:00:00 +0100
tags: graph chart-types
categories: data visualization
comments: false
---

![Illustration image](/assets/images/chart-types/graph_structure.jpg "Foto: Csilla Szántó")

# Seeing Relationships: Why Graphs Matter in AI and Beyond

## Graphs & Networks in the Age of AI

{% for tag in page.tags %}
<code>#{{ tag }}</code>{% endfor %}

<br/>

This week I attended TDC São Paulo virtually. One talk that particularly caught my attention was by Fabiane Nardon, who discussed how structured context, RDF and ontologies can help LLMs reduce hallucinations.

If you haven't come across RDF before, here's the short version: it represents relationships as simple triples - *subject → predicate → object*.

For example:

*Alice → knows → Bob*

Computers can process these triples efficiently, and when enough of them are connected, they form a **knowledge graph**.

For machines, RDF is powerful. For humans, however, reading thousands of triples isn't exactly intuitive. We quickly lose sight of the bigger picture.

That led me to an interesting thought: just as LLMs need structured context to reduce hallucinations, humans need visualization to avoid seeing relationships that aren't really there.

And that's where **graphs** come in.

<br/>

## What Is a Graph?

At its core, a graph is a representation of relationships.

A graph consists of:

* **Nodes (vertices)** - entities such as people, systems, products, or concepts.
* **Edges (links)** - the relationships between them, such as *reports to*, *owns*, or *connects with*.

Instead of looking at isolated data points, you see how everything is connected.

Social networks, transport routes, organizational structures are all examples of graph-based models. Edges, that is connections, can be directed or not.

<br/>

## Why Graphs Are So Useful

Humans are naturally good at spotting patterns visually.

Graphs make those patterns easier to see:

* In **IT monitoring**, they help reveal bottlenecks.
* In **social networks**, they expose communities and influential nodes.
* In **knowledge graphs**, they show how concepts relate to one another.

RDF and ontologies provide structured understanding for machines. Graphs provide a bird's-eye view for humans.

Together, they make complex systems easier to understand.

<br/>

## Common Ways to Visualize Graphs

There are several approaches to representing graph data.

### 1. Node-Link Representations

The classic approach: nodes are shown as dots and edges as connecting lines.

This works well for small and medium-sized networks, although larger graphs can become cluttered. Layout algorithms help determine where nodes and edges should be placed for better readability.

### 2. Matrix Representations

Instead of drawing connections, relationships are shown in a matrix where rows and columns represent nodes.

This avoids visual clutter and can scale better, but it is often less intuitive for people.

### 3. Implicit Representations

In these visualizations, relationships are implied by the position of elements rather than explicit links.

This approach works particularly well for hierarchical structures such as trees.

<br/>

## Where Graphs Create Value

Graphs are useful wherever relationships matter more than individual records.

Some examples include:

* **Enterprise knowledge graphs** for connecting information across silos.
* **Security analytics** for identifying suspicious connections.
* **Biology and life sciences** for studying molecular and genetic interactions.
* **Business modeling** for visualizing supply chains, processes, and organizational structures.
* **AI systems**, where knowledge graphs increasingly support context-aware and trustworthy agents.

<br/>

## Tools Worth Exploring

If you'd like to experiment with graph visualizations, these are good starting points:

* **NetworkX** (Python) for coding and graph analysis.
* **d3.js** for highly customizable interactive web visualizations.
* **Highcharts** for creating interactive graphs with relatively little code.

<br/>

Listening to the discussion around RDF and ontologies felt familiar. Years ago, I worked with taxonomies and ontologies in enterprise search, and it is interesting to see these concepts reappear as building blocks in modern AI architectures.

Another session explored agentic GraphRAG. While the implementation differs from traditional knowledge graph approaches, the underlying idea is similar: use graph structures to better connect and retrieve information.

By understanding relationships rather than just matching text, graph-based RAG systems can often deliver more relevant results, improve information correlation, and help reduce hallucinations.

Technology evolves, but the challenge remains the same: making sense of complex information. Graphs continue to be one of the most effective ways to do exactly that.

Have you worked with graph visualizations before? If not, try taking a dataset you know well and sketching it as a graph - you may discover connections that were hidden before.

{%- include ebook.html -%}
