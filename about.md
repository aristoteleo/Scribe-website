---
layout: default
permalink: /
tags: [Scribe, scRNA-Seq, single-cell]
modified: 2018-01-26
---

Scirbe provides a powerful toolkit for visualizing and inferring complex causal gene regulation from single cell genomics data. At the core of Scribe, we used restricted direct information, which has been shown to out-performan than "symmetric"mutual information, "linear" Granger causality and the newly proposed "deterministic"CCM method. The users of Scribe are expected to have already correctly reconstructed the developmental trajectory for their single-cell genomics dataset with Monocle 2 as it relies on the pseudotime resolved data to infer the network causality.

Scirbe is a collaboration between Trapnell lab at UW Genome Sciences department and Kannan lab at UW Electrical Engineering department.

Scribe is provided under the OSI-approved Artistic License (version 2.0)

# News

*To get the latest updates on the Scribe project and the rest of the "Tuxedo tools", please subscribe to our [**mailing list**](https://lists.sourceforge.net/lists/listinfo/bowtie-bio-announce)*

<ul class="post-list">
{% for post in site.posts %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>
