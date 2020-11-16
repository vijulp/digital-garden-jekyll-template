---
layout: page
title: Home
id: home
permalink: /
---

# Hi! I'm Vijul 👋 

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p>

I'm a Cloud Solutions Architect based in Toronto. I work with customers to accelerate their cloud adoption journey. Areas of interest include cloud computing, cryptocurrency, and clean energy. 

I'm active on <a title="Twitter" rel="noopener" target="_blank" href="https://twitter.com/vijulp">Twitter</a> &mdash; direct messages are open! Say hi! 👋

<div>
    <div class="grid-element">
      <h2>Blog posts</h2>
      {% assign post_limit = 7 %}
      {% for post in site.posts limit: post_limit %}
      <div class="list-entry">
        <div><a class="internal-link" href="{{ post.url }}">{{ post.title }}</a> <span class="faded">({{ post.date | date: "%Y-%m-%d" }})</span></div>
        <div>{{ post.excerpt }}</div>
      </div>
      {% endfor %}
    </div>


<style>
  .wrapper {
    max-width: 46em;
  }
</style>
