---
title: "Aldébaran Diorama"
date: 2020-06-08T08:06:25+06:00
description: Sample post with multiple images, embedded video etc.
menu:
  sidebar:
    name: Aldébaran Diorama
    identifier: adebaran-diorama
    parent: mini-projects
    weight: 1
hero: images/hero.jpg
tags:
- Markdown
- Content Organization
- Multi-lingual
categories:
- Basic
---
## Context

## Video

<div style="display: flex;">
  <!-- Text Zone on the Left -->
  <div style="flex: 1; padding: 10px; border-right: 1px solid #ccc;">
    <p>This is where you can add your text. You can write anything here, such as a description of the video, notes, or other content.</p>
  </div>

  <!-- Video on the Right -->
  <div style="width: 490px; padding: 10px;">
    <video width="490" height="300" controls>
      <source src="/posts/3-light/1-container/images/video1.mp4" type="video/mp4">
    </video>
  </div>
</div>
<br><br><br>

<div style="display: flex;">
  <!-- Text Zone on the Left -->
  <div style="flex: 1; padding: 10px; width: 510px">
    <video width="490" height="300" controls>
      <source src="/posts/3-light/1-container/images/video2.mp4" type="video/mp4">
    </video>
  </div>

  <!-- Video on the Right -->
  <div style=" padding: 10px; border-left: 1px solid #ccc;">
  <p>This is where you can add your text. You can write anything here, such as a description of the video, notes, or other content.</p>
    
  </div>
</div>


This sample post tests the followings:

- Category, sub-category nesting in the sidebar.
- Hero image and other images are in `images` folder inside this post directory.
- Different media rendering like image, tweet, YouTube video, Vimeo video etc.

### Image Sample

{{< img src="/posts/category/sub-category/rich-content/images/forest.jpg" align="center" title="Forest">}}

{{< vs >}}

### Tweet Sample

{{< tweet user="SanDiegoZoo" id="1453110110599868418" >}}

{{< vs >}}

### YouTube Video Sample

{{< youtube ZJthWmvUzzc >}}

{{< vs >}}

### Vimeo Video Sample

{{< vimeo 48912912 >}}
