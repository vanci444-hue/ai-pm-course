# AI PM Course

An AI Product Manager curriculum built for people switching into AI product roles.

## Overview

`ai-pm-course` hosts the course site, outline, and teaching materials for a structured AI Product Management curriculum. It is designed to take someone with product or adjacent experience and move them toward real competence in shipping AI-powered products.

The site is a static web experience — no build step, no backend — so it can be read directly on GitHub Pages.

## Why it exists

Most existing "AI PM" content is either vendor marketing or fragmented blog posts. Career switchers need a coherent path: from how LLMs actually behave, to how to scope an AI feature, to how to evaluate and ship it.

This course is the path I wish existed when I started.

## Features

- Structured weekly curriculum (W01–W04 and beyond), iteratively versioned
- A full course outline page covering scope, learning objectives and session breakdown
- Embedded visual explainers (e.g. a Transformer walkthrough linked from `transformer-cyberpunk`)
- Designed to be read on a phone or laptop without extra tooling

## Project Structure

```
.
├── index.html          # Course homepage (entry point)
└── course-outline.html # Detailed session-by-session outline
```

## Preview / Demo

- Homepage: https://vanci444-hue.github.io/ai-pm-course/
- Outline: https://vanci444-hue.github.io/ai-pm-course/course-outline.html

Enable GitHub Pages on `main` branch, root directory, to publish.

## Tech Stack

- Static HTML / CSS / vanilla JS
- Served via GitHub Pages
- No framework, no build step

## Author

**Evan** — AI Product Manager, currently practicing at an AI company and teaching AI PM fundamentals on the side.
