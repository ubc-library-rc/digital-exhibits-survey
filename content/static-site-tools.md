---
layout: default
title: Wax and CollectionBuilder
nav_order: 6
has_children: false
has_toc: false
---
# Static sites

Static websites differ from dynamic websites in that they are not in consistent communication with a server. In other words, all of the data loads when you access the site and as you interact with it it's pre-loaded in your browser. As a result static sites are very self-contained and computationally reproducible which gives them longevity. This is particularly important in an academic context.

# Minimal Computing
Using a static site approach for digital exhibits falls into a way of thinking about digital scholarship that prioritises longevity and different types of "minimalism". That doesn't necessarily mean that the project is simple just that it has characteristics that will make it durable.

The goal is to answer two questions:
* Who will be able to see your work in 10 years?
* Will they be able to see it or <strong>use it</strong>?

Minimal might mean:
* Constrained
* Underfunded
* Fewer total number of technologies
* Easier to maintain long-term
* Fewer <strong>"dependencies"</strong>
* Formats that are <strong>"future proofed"</strong>

Read more about Minimal Computing here: https://go-dh.github.io/mincomp/about/
{: .note}

# Avoiding technical debt
Technical debt refers to the ongoing operational and maintenance needs of a digital project that go beyond the core project work. It accumulates over time and is difficult to offset. The best solution to technical debt is to have a coherent "sunsetting" plan which establishes how your project will be preserved, taken offline at a specific date, and in what form it will remain accessible to future generations. Minimal computing can help mitigate some of the complexity that can arise from technical debt by making use of open file formats, few dependencies, and keeping everything that relates to the project together in one place. This means that there is a higher likelihood your project will remain accessible into the future even if it is no longer active and be easier to replicate or build onto.

Free as in kitten not free as in beer.

# Wax
[Wax](https://minicomp.github.io/wax/) is a minimal computing publishing tool for the creation of academic digital exhibits using a IIIF viewer.
* Leverages <a href="https://jekyllrb.com/" target="_blank">Jekyll</a> and Github Pages
* Uses <a href="https://iiif.io/" target="_blank">IIIF (International Image Interoperability Framework)(<a href="https://docs.google.com/document/d/1h9SPg9nlLA3TAdzkYxkyaFFNNf8m4PsbaIExcYwVLyo/edit#heading=h.q7mmne7d3bk2" target="_blank">why IIIF?</a>)
* Uses <a href="https://openseadragon.github.io/" target="_blank">OpenSeaDragon</a> viewer but can use any other
* Creates a relatively small static site (vs. dynamic)

# CollectionBuilder
"[CollectionBuilder](https://collectionbuilder.github.io/) is an open source tool for creating digital collection and exhibit websites that are driven by metadata and powered by modern static web technology."
* Similar to Wax in it's use of Jekyll, Ruby, and Github Pages, creating a small static site
* Focus on metadata creation as a core element of scholarly output
* Three versions, one for Github Pages based exhibits, one as a front layer for repositories, and one as a standalone tool
