# Process: Assignment 01

## Prompt

**Why are we here?**

## Initial Idea

I am an art and design student who is new to programming. I wanted to make a generative artwork that I could develop by looking at the visual results and deciding what to change. I started with a repeated square because it gave me a clear and simple structure to work from.

## Reference

The artwork was inspired by Georg Nees' *Schotter* (1968). I used the idea of an ordered grid that gradually becomes disordered, while making my own changes to the size and colour of the squares.

## Starting System

The first version used an ordered grid of repeated squares. The squares began in regular positions and created a stable pattern. GitHub Copilot helped me generate and modify the Python code for the artwork. I also used AI to help organise and draft parts of the written reflection, but I reviewed and edited that writing myself.

## Iterations

### Iteration 1: Ordered Grid

The ordered grid gave me a clear starting point. The repeated squares looked stable and controlled, which made it possible to see the changes in the later versions.

### Iteration 2: Falling-Apart Structure

AI helped implement rotation and displacement so the squares became increasingly disordered toward the bottom. The initial `CHAOS` value was `1.0`. After looking at the generated image, I decided that the transition from order to disorder was too weak, so I changed `CHAOS` to `2.0`. The stronger value made the falling-apart effect much clearer.

### Iteration 3: Changing Scale

After increasing the disorder, I decided that the lower part should feel less stable. I made the squares gradually become smaller toward the bottom. This made the lower section feel less solid and helped the artwork move beyond simply being a disordered grid.

### Iteration 4: Fading Colour

I then decided that the outlines should fade from black to light grey. Together with the smaller squares and increased movement, the fading made the lower squares feel as if they were disappearing rather than only becoming disordered.

## Technical Decisions

- Disorder and movement: rotation and displacement increase toward the bottom of the grid.
- Chaos: I changed the value from `1.0` to `2.0` after judging the first generated image.
- Size progression: the squares gradually become smaller toward the bottom.
- Colour progression: the outlines gradually change from black to light grey.
- AI implementation: GitHub Copilot helped generate and modify the Python code.
- Written reflection: AI helped organise and draft parts of the reflection, which I reviewed and edited myself.

## Observations

The most important part of the process was looking at each generated result and deciding what needed to change. The code could produce the requested changes, but I had to decide whether the visual result matched my intention. Increasing `CHAOS`, reducing the square size, and fading the outlines made the movement from order toward disappearance clearer.

## AI Disclosure

I used GitHub Copilot to help generate and modify Python code for the generative artwork. I also used AI to help organise and draft parts of the written reflection. I reviewed and edited the written results myself.

### Kept

I kept the AI-assisted code changes for increasing disorder, changing the square size, and fading the outlines. I kept them because they successfully implemented the visual changes I wanted after I evaluated the generated images.

### Rejected

I rejected an early AI-assisted interpretation of the essay question "Why are we here?" It focused too much on the artwork concept and did not directly answer the assignment question: why an artist or designer should learn programming in 2026 when AI can already generate code. After rereading the assignment brief, I restructured the essay so it answered that question more directly.

## Questions for Further Development

- What would happen if the fall-off were slower or faster?
- How would a different repeated shape change the meaning?
- What role would a different set of code instructions play in the work?

## Final Reflection

This process showed me that using AI for code does not remove the need for my own programming knowledge or judgement. I needed to understand enough to describe changes, recognise what the code was doing, and decide whether the image worked. AI helped me implement the artwork, but I remained responsible for choosing the direction of the work and deciding what to keep or reject.
