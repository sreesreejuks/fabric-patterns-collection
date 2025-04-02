# Tweet 🐦✨

## Overview

**Tweet** is a Fabric pattern designed for crafting concise, engaging, and tone-appropriate tweets. It takes input text or concepts and transforms them into audience-specific tweets, carefully incorporating the requested tone, sentiment, and purpose. 

This pattern uses hashtags (e.g., `#sarcasm`, `#angry`, `#compassion`) embedded in the input to guide the tone and sentiment of the tweet. It leverages best practices like emoji integration, strategic hashtag use, and a focus on interaction to create high-performing tweets. 

💡 **Tweet** ensures every tweet is aligned with the desired audience and purpose while staying within the 280-character limit.
---

## How It Works ⚙️

1. **Input Parsing**:
   - Reads the input text, identifying the purpose, target audience, and any hashtags specifying tone or sentiment (e.g., `#sarcasm`, `#angry`).

2. **Tone and Context Application**:
   - Applies the requested tone or sentiment to the tweet. If none is explicitly stated, it infers the tone from the context or defaults to neutral/positive.

3. **Tweet Creation**:
   - Crafts a tweet using clear language, emojis, and relevant hashtags, ensuring alignment with the input context.

4. **Output Formatting**:
   - Provides the final tweet in plain text, ready for immediate posting.

