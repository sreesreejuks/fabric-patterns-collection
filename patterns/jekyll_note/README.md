<div align="center">

<img src="https://raw.githubusercontent.com/sreeju/fabric-patterns-collection/main/patterns/jekyll_note/jekyll-logo.png" alt="jekylllogo" width="400" height="400"/>

# `/jekyll_note`

<h4><code>jekyll_note</code> is a <a href="https://github.com/danielmiessler/fabric" target="_blank">Fabric</a> pattern that <em>creates Jekyll-compatible blog posts</em> from any text input.</h4>

[Description](#description) •
[Functionality](#functionality) •
[Usage](#usage) •
[Output](#output) •
[Meta](#meta)

</div>

<br />

## Description

**`jekyll_note` addresses the problem of creating well-structured, Jekyll-compatible blog posts from any text input.**

This pattern helps you create properly formatted Markdown files that are ready to be used with Jekyll static site generator, ensuring:

- Proper YAML front matter
- Consistent formatting
- Well-structured content
- Automatic table of contents generation
- SEO-friendly headings and links

## Functionality

When you use `jekyll_note`, it generates a complete Jekyll-compatible Markdown file with:

- **YAML Front Matter**
  - Title (auto-generated from content)
  - Layout (set to 'post')
  - Author (set to 'sreeju')
  - Date (current date and time)
  - Categories (1-3 relevant categories)
  - Tags (3-5 relevant tags)

- **Content Structure**
  - Table of Contents with proper Markdown heading links
  - Logical content flow from basic to advanced concepts
  - Proper sentence structure and detailed explanations
  - Code blocks where necessary
  - Bullet points, numbered lists, and tables where applicable
  - SEO-friendly heading structure

## Usage

You can reference the `jekyll_note` **system** content directly like so:

```sh
curl -sS https://github.com/sreeju/fabric-patterns-collection/blob/main/patterns/jekyll_note/system.md
```

## Output

Here's an example output from `jekyll_note`:

```markdown
---
title: Understanding Jekyll Blog Posts
layout: post
author: sreeju
date: 2024-04-02 09:33:00 -0700
categories: [web-development, static-sites]
tags: [jekyll, markdown, blogging, documentation]
---

## Table of Contents
* [Introduction](#introduction)
* [Key Concepts](#key-concepts)
* [Implementation](#implementation)
* [Best Practices](#best-practices)

## Introduction

[Content follows with proper structure and formatting...]
```

This allows you to quickly create well-structured, Jekyll-compatible blog posts from any text input.

## Meta

- **Author**: Sreeju
- **Version Information**: Initial version
- **Published**: April 2, 2025 