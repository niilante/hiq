---
layout: docs
title: Media
description: HiQ applies responsive styles to your media elements out of the box.
toc: true
group: guide
---

## Responsive media

Media elements, including `img`, `embed`, `object`, and `video` are made responsive in HiQ by default. Their `max-width` is set to 100% of their container width.

## Images

`img` elements are given a border-radius by default. This can be altered with `--hiq-image-border-radius`.

<img src="{{ site.baseurl }}/assets/img/placeholder.svg" alt="Image alt text">

{% include properties-table.html category="images" %}

## Figures

Anytime you need to display a piece of content like an image with an optional caption, consider using a `<figure>`. Some baseline styles are provided for the HTML5 `<figure>` and `<figcaption>` elements.

{% example html %}
<figure>
    <img src="{{ site.baseurl }}/assets/img/placeholder.svg" alt="Image alt text">
    <figcaption>Here is a caption for this image.</figcaption>
</figure>
{% endexample %}

{% include properties-table.html category="figures" %}

## iFrames

By default, the border around `iframe`s is removed.
