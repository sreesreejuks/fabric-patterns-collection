# video-to-obsidian

## Description
This pattern extracts content from tutorial videos and transforms it into comprehensive, well-structured Obsidian-friendly documentation. It works particularly well for technical tutorials (programming, system administration, DevOps, etc.) that involve commands, configurations, and step-by-step procedures.

## How It Works
1. You provide a URL to a tutorial video
2. The pattern instructs Claude to analyze the video content
3. Claude extracts key information and creates structured Markdown documentation optimized for Obsidian
4. The output includes proper formatting, code blocks, headings, tags, and other Obsidian features

## Example Use Cases
- Converting Linux tutorial videos to reference documentation
- Creating searchable knowledge base entries from video courses
- Building a personal technical documentation library from YouTube tutorials
- Documenting complex procedures from video walkthroughs
- Generating Obsidian notes from conference talks or technical presentations

## Sample Input
```
https://www.youtube.com/watch?v=U1VzcjCB_sY
```

## Sample Output
A comprehensive Markdown document with:
- Clear title and summary
- Prerequisites section
- Step-by-step instructions with proper heading hierarchy
- Code blocks with syntax highlighting
- Configuration examples
- Troubleshooting tips
- Obsidian-specific formatting (tags, callouts, etc.)

## Notes
- Works best with tutorial videos that have clear structure and technical content
- The pattern emphasizes capturing technical details (commands, configurations, etc.)
- The output is ready for import into Obsidian without additional formatting
- Can be used with any tutorial video URL, though results may vary based on video quality and content clarity
