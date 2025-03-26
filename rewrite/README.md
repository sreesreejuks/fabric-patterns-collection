# Rewrite Pattern 🖋️🔄

## Overview 🧩

**Rewrite** is a Fabric pattern designed to transform the input text according to specified or default variables, including **speaker** (impersonation), **tone** (formal, funny, etc.), and **style** (human, robot, or unchanged). Its primary purpose is to preserve meaning while adjusting the text’s style, tone, and persona.  

- **Variable Extraction**: Extracts and applies `'speaker=...'`, `'tone=...'`, and `'style=...'`.
- **Default Behavior**: When no variables are provided, Rewrite defaults to a natural, human-like rewrite.
- **Usage example**: In this example we are adding a line containing the variables on top of the contents of the clipboard. `paste` is an alias to get the contents of the clipboard, can be replaced by `cat filename` or similar.

`(echo 'style=human speaker=donald trump tone=funny\n' && paste) | fabric -p rewrite --stream` 

---

## Output 📋

`Rewrite` outputs a rewritten version of the given text in Markdown format, following these core principles:

### **1. Variable-Based Transformation** ✨
- **Speaker Impersonation**: If `speaker` is detected, the rewritten text reflects that speaker’s typical style or phrasing.  
- **Tone Adjustment**: If `tone` is specified (e.g., funny, formal, persuasive, angry, sarcastic), the output aligns with the chosen tone.  
- **Style Selection**: If `style` is set to `human` or `robot`, the text adopts that style. Otherwise, the style remains unchanged.

### **2. Humanizing & Specificity** ❤️
When a human style is requested or no style is given, the focus is on diversity in wording, sentence openings, and transitions. The pattern replaces generic or repetitive phrases with specific details, creating a more engaging and authentic human-like tone. This would hopefully fool AI detectors. Associating with a persona will increase the chances of fooling AI detectors even more.

---

## Features 🌟

- **Variable Extraction**: Automatically detects `speaker=...`, `tone=...`, and `style=...` from the input text.
- **Tone & Style Flexibility**: Adapts output to formal, funny, persuasive, or any specified tone; switches between a human-like or robot-like style.
- **Structural Integrity**: Retains paragraph breaks and overall text structure, aiming for readability and coherence.
- **Humanization Guidelines**: Provides a host of “AI Style to Avoid” vs. “Human Style to Adopt” rules for crafting natural-sounding text.

---

## Credits 🙌

Rewrite is an iteration of the `humanize` pattern.
