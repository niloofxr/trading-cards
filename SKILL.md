---
name: trading-card-skill
description: Create polished trading cards with a framed layout, core stats, artwork, descriptions, and rarity badges.
---

# Trading Card Skill

Use this skill whenever the user asks to create, design, or generate a trading card.

## Card specification

- Use a polished portrait card with a rounded-corner frame and clear visual hierarchy.
- Put a prominent name banner across the top.
- Include a large rectangular artwork area with a distinct black border.
- Show exactly three core stats: **Power**, **Speed**, and **Creativity**. Ask for values only if needed; otherwise choose balanced values that fit the character.
- Add a concise one-sentence description.
- Add one circular rarity badge in the **top-right corner**, labeled exactly **Common**, **Rare**, or **Legendary**, with a visibly sparkly border.

## Execution guidance

Preserve every required element in the final composition. Keep text legible at card size, align the stats consistently, and reserve the top-right corner for the rarity badge so it remains clearly visible and does not overlap the name banner or artwork. If the user provides a style, character, colors, or image, treat those as the source of truth while retaining this structure. If they ask for an image asset, use the image-generation workflow; if they ask for code or a UI, implement the same specification in that medium.
