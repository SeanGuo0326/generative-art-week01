# Assignment 01: "Why are we here?"

## Project

A generative artwork inspired by Georg Nees's *Schotter* (1968). The piece begins as an ordered grid of squares and gradually falls apart as it moves downward.

## Concept

This project explores why an artist or designer should learn programming in 2026, when AI can already generate working code from natural-language prompts. My main argument is that I do not need to learn programming in order to compete with AI at writing code. I need to understand programming well enough to direct AI, understand and evaluate what it produces, and make my own creative decisions.

## How to Run

This project uses only Python's standard library.

```bash
python sketch.py
```

Running the script generates `sketch.svg` in the repository directory. Open the SVG in a browser to view the artwork.

## Current Parameters

- `COLS`: Number of squares across
- `ROWS`: Number of rows
- `SEED`: Random seed for a repeatable result
- `CHAOS`: Controls how quickly the grid breaks apart
- `SQUARE`: Starting square size

## Files

- `sketch.py`: Source code for the generative artwork
- `sketch.svg`: Latest generated image
- `PROCESS.md`: Working notes, iterations, and development process

## Essay Outline: Why Are We Here?

**Target length: 500-1000 words**

### 1. Introduction: The Question in 2026

In 2026, AI can generate working code from a natural-language prompt. As an art and design student who is new to programming, this makes me question why I should learn it. If AI can write code faster than I can, my goal should not be to compete with it. I am learning programming so I can understand what AI is doing, give it precise instructions, and decide whether its results are useful for my work. AI can speed up a technical process, but it cannot decide what I want an artwork to communicate. I still need to judge the result and choose what should change.

### 2. What Learning Programming Means Now

Learning programming does not mean writing every line from memory. It means understanding enough to follow what a program is doing. I need to recognise variables, parameters, loops, and randomness, and understand how changing them can change an image. This lets me describe a visual change more precisely, ask AI for a useful modification, and evaluate whether the result matches my intention. Without this understanding, I would depend on suggestions I could not properly question. I am not trying to become a better code writer than AI. I am trying to become an informed artist who can use AI while keeping responsibility for the direction and creative decisions in my work.

### 3. Example: Starting the Generative Artwork

- Describe the ordered grid of repeated squares, inspired by Georg Nees' *Schotter* (1968).
- Explain that AI helped generate and modify the Python code for the artwork.
- Emphasise that receiving code was only the beginning: the important decisions came from looking at the visual result and deciding whether it worked.

### 4. Example: Directing and Evaluating AI Output

- Explain that the first `CHAOS` value was `1.0`.
- Describe judging the result and deciding that the transition from order to disorder was not strong enough.
- Explain the decision to change `CHAOS` to `2.0` and how this made the visual change more noticeable.
- Connect this to programming knowledge: understanding the parameter made it possible to ask for a specific change and evaluate the result.

### 5. Example: Making Creative Decisions Beyond the Prompt

- Describe deciding to make the squares gradually smaller toward the bottom.
- Describe the final decision to fade the outlines from black to light grey.
- Explain that these choices made the squares feel as if they were disappearing.
- Point out that AI could help implement these ideas, but it could not replace the personal judgement about what the artwork should communicate.

### 6. Why This Matters for Artists and Designers

- Argue that programming knowledge helps artists move from accepting AI output to shaping it.
- Explain that the artist still needs to know what they want, notice when the result is weak, and decide what to change next.
- Mention that understanding code also makes it easier to spot limitations, unexpected behaviour, and differences between the requested idea and the actual result.

### 7. Conclusion: Learning to Direct, Not Compete

- Return to the question of why to learn programming when AI can write code.
- Conclude that the goal is not to beat AI at producing syntax.
- State that programming knowledge gives the artist enough understanding to collaborate with AI while keeping authorship, judgement, and creative direction.
- End by connecting the artwork to the argument: AI helped produce the tools, but the artistic decisions came from observing, evaluating, and choosing what should happen next.
