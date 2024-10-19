---
layout: archive
title: "Projects"
description: "My current and previous projects."
permalink: /projects/
author_profile: true
output: 
  html_document:
    keep_md: true
---
## Make RStudio a friend, not a foe.

Welcome to my RStudio tutorial 🎉! As a passionate data enthusiast, I created this tutorial to help beginners and intermediate users confidently dive into R programming.

<!-- 左右排列的區塊 -->
<div style="display: flex; align-items: flex-start;">
  <!-- 左邊內容 -->
  <div style="flex: 1; max-width: 600px; padding-right: 20px;">
    <p>🌐 <a href="https://cocoyamo.github.io/R_tutorials/">Web Tutorial</a>: Covering key topics like data import, cleaning, visualization, and statistical analysis using <strong>tidyverse</strong> and <strong>ggplot2</strong>.</p>
    <p>🎥 <a href="https://www.youtube.com/playlist?list=PLrnPgbLdSy7czQs7mrJNR9XQxH75OjvcU">Tutorial Videos</a>: Boost your learning with step-by-step videos that make it easier to master R and turn it into a powerful ally 🪄.</p>
    <p>By the end, you'll have the skills to perform effective data analysis and create compelling visualizations, enhancing your confidence and abilities in R.</p>
  </div>
  <!-- 右邊影片 -->
  <div style="flex: 0 0 auto; text-align: right;">
    <p><iframe style="width: 320px; height: 180px;" src="https://www.youtube.com/embed/nQcVh9_infA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>

## What does your brain look like while solving math problems?

<img align="left" width="320" src='/images/wholebrain_interaction.jpg'>

`# math word problem` `# fronto-insular-parietal network` `# lexical consistency` `# fMRI` 

***"Tom has 6 books. Jerry has 10 books more than Tom. How many books does Jerry have?"*** This is a common math word problem where we apply abstract math operations to real-life situations.

However, when solving these problems, we often come across different ways of phrasing the same concept. For example, ***"Joe has 6 books. Amy has 2 books **less** than Joe. How many books does Joe have?"***

When the wording changes, the relationship between the numbers becomes harder to figure out.

We discovered a developmental shift, where children are more easily affected by lexical inconsistencies compared to adolescents. However, for adolescents, the consistency effect re-emerges when solving addition problems. This effect is evident in both their [brain](https://cocoyamo.github.io/publications/2024-04-15-age-related_differences_in_brain_responses_in_mathematical_problem-solving_among_children_and_adolescents)  and [behavioral](https://cocoyamo.github.io/publications/2022-10-15-development-of-operation-specific-lexical-consistency-effect-in-arithmetic-word-problem-solving) data.

## The Influence of Emotional Schema and Color Congruency on the Trustworthiness of News

`# emotions` `# color schema` `# news trustworthiness`

Publications
-----
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Collaborations
-----
  <ul>{% for post in site.collaborations reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
