<div align="center">

<img src="https://raw.githubusercontent.com/sreeju/fabric-patterns-collection/main/patterns/jekyll_post/jekyll-logo.png" alt="jekylllogo" width="400" height="400"/>

# `/jekyll_post`

<h4><code>jekyll_post</code> is a <a href="https://github.com/danielmiessler/fabric" target="_blank">Fabric</a> pattern that <em>transforms any text into a well-formatted Jekyll blog post</em>.</h4>

[Description](#description) •
[Functionality](#functionality) •
[Usage](#usage) •
[Output](#output) •
[Meta](#meta)

</div>

<br />

## Description

**`jekyll_post` addresses the problem of quickly creating engaging, well-structured blog posts for Jekyll websites.**

This pattern takes any input text and transforms it into a properly formatted Jekyll blog post, ensuring:

- Professional blog post structure
- Proper YAML front matter
- Engaging content flow
- Appropriate formatting and styling
- SEO-friendly metadata

## Functionality

When you use `jekyll_post`, it generates a complete Jekyll blog post with:

- **YAML Front Matter**
  - Title (auto-generated from content)
  - Layout (set to 'post')
  - Author (set to 'sreeju')
  - Date (current date and time)
  - Categories (1-3 relevant categories)
  - Tags (3-5 relevant tags)

- **Content Structure**
  - Well-written blog post format
  - Logical content flow
  - Proper sentence structure and engaging explanations
  - Code blocks where necessary
  - Bullet points, numbered lists, and tables where applicable
  - SEO-friendly heading structure

## Usage

You can reference the `jekyll_post` **system** content directly like so:

```sh
curl -sS https://github.com/sreeju/fabric-patterns-collection/blob/main/patterns/jekyll_post/system.md
```

## Output

Here's an example output from `jekyll_post`:

```markdown
---
title: The Future of AI in Web Development
layout: post
author: sreeju
date: 2024-04-02 09:33:00 -0700
categories: [technology, web-development]
tags: [ai, machine-learning, web-dev, future-tech]
---

# The Future of AI in Web Development

Artificial Intelligence is revolutionizing how we approach web development. From automated code generation to intelligent user interfaces, AI tools are becoming an integral part of the modern developer's toolkit.

## Current State of AI in Web Dev

[Content continues with proper blog post structure and formatting...]
```

This allows you to quickly transform any text into a well-structured, engaging Jekyll blog post.

## Meta

- **Author**: Sreeju
- **Version Information**: Initial version
- **Published**: April 2, 2025 