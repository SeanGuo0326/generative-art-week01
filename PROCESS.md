# Process: Assignment 01

## Prompt

**Why are we here?**

## Initial Idea

I am an art and design student who is new to programming. The tutor provided the starting Python code as a class exercise, and it gave me a clear and simple structure to understand and modify. I wanted to develop the artwork by looking at the visual results and deciding what to change.

## Reference

The tutor-provided class exercise was based on Georg Nees' *Schotter* (1968-1970). I worked with the idea of an ordered grid that gradually becomes disordered, while making my own changes to the movement, size, and colour of the squares.

## Starting System

The tutor's starting code used an ordered grid of repeated squares. The squares began in regular positions and created a stable pattern. I used GitHub Copilot to help me understand and modify the existing Python code. I also used AI to help organise and draft parts of the written reflection, but I reviewed and edited that writing myself.

## Iterations

### Iteration 1: Ordered Grid

The tutor-provided ordered grid gave me a clear starting point. The repeated squares looked stable and controlled, which made it possible to see the changes in the later versions.

### Iteration 2: Falling-Apart Structure

The tutor-provided code already used rotation and displacement so the squares became increasingly disordered toward the bottom. I used AI to help me understand how this existing system worked. The initial `CHAOS` value was `1.0`. After looking at the generated image, I decided that the transition from order to disorder was too weak, so I changed `CHAOS` to `2.0`. The stronger value made the falling-apart effect much clearer.

### Iteration 3: Changing Scale

After increasing the disorder, I decided that the lower part should feel less stable. I made the squares gradually become smaller toward the bottom. This made the lower section feel less solid and helped the artwork move beyond simply being a disordered grid.

### Iteration 4: Fading Colour

I then decided that the outlines should fade from black to light grey. Together with the smaller squares and increased movement, the fading made the lower squares feel as if they were disappearing rather than only becoming disordered.

## Technical Decisions

- Disorder and movement: rotation and displacement increase toward the bottom of the grid.
- Chaos: I changed the value from `1.0` to `2.0` after judging the first generated image.
- Size progression: the squares gradually become smaller toward the bottom.
- Colour progression: the outlines gradually change from black to light grey.
- AI implementation: GitHub Copilot helped me understand and modify the tutor-provided Python code.
- Written reflection: AI helped organise and draft parts of the reflection, which I reviewed and edited myself.

## Observations

The most important part of the process was looking at each generated result and deciding what needed to change. The code could produce the requested changes, but I had to decide whether the visual result matched my intention. Increasing `CHAOS`, reducing the square size, and fading the outlines made the movement from order toward disappearance clearer.

## AI Disclosure

I used GitHub Copilot to help me understand and modify the tutor-provided Python code for the generative artwork. I also used AI to help organise and draft parts of the written reflection. I reviewed and edited the written results myself. My creative decisions included increasing `CHAOS` from `1.0` to `2.0`, making the squares gradually smaller, and changing the outlines from black to light grey after evaluating the visual results.

### Kept

I kept the AI-assisted modifications that helped me adjust the existing `CHAOS` system, make the squares gradually smaller, and fade the outlines. I kept them because they successfully implemented the visual changes I wanted after I evaluated the generated images.

### Rejected

I rejected an early AI-assisted interpretation of the essay question "Why are we here?" It focused too much on the artwork concept and did not directly answer the assignment question: why an artist or designer should learn programming in 2026 when AI can already generate code. After rereading the assignment brief, I restructured the essay so it answered that question more directly.

## Questions for Further Development

- What would happen if the fall-off were slower or faster?
- How would a different repeated shape change the meaning?
- What role would a different set of code instructions play in the work?

## Final Reflection

This process showed me that using AI with existing code does not remove the need for my own programming knowledge or judgement. I needed to understand the tutor-provided code well enough to describe changes, recognise what it was doing, and decide whether the image worked. My decisions to increase `CHAOS` from `1.0` to `2.0`, make the squares smaller, and fade the outlines came from evaluating the visual results. AI helped me modify the artwork, but I remained responsible for choosing its direction and deciding what to keep or reject.
