---
layout: article
title: Orishas
permalink: /orishas.html
aside:
  toc: true
sidebar:
  nav: sidebar-orishas
articles:
  data_source: orishas
---


Learn more about the orishas, click the links in the sidebar.

Did it update 3

<div class="layout--articles">
  <section class="my-5">
    <header><h2 id="page-layout">Page Layout</h2></header>
    {%- include article-list.html articles=site.orishas type='grid' -%}
  </section>

  <section class="my-5">
    <header><h2 id="articles-layout">Articles(Home) Layout</h2></header>
    {%- include article-list.html articles=orishas type='grid' -%}
  </section>

</div>
