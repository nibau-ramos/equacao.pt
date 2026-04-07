# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static single-page website for **EQUAÇÃO PTV**, a Portuguese civil engineering firm (Projectos, Fiscalização & Gestão). The site is written in plain HTML/CSS with no build tools, frameworks, or dependencies.

## Development

Open `src/index.html` directly in a browser — no build step, no server required.

## Architecture

Everything lives in `src/index.html`: all HTML structure, CSS (inline `<style>` block), and content. There is no JavaScript. Assets are three logo variants (`logo.png`, `logo-white.png`, `logo-black.png`) also in `src/`.

The page is structured as three anchor-linked sections:
- `#inicio` — hero with `logo-white.png`
- `#servicos` — services grid
- `#contactos` — contact info + embedded Google Maps iframe

Brand color: `#5d4351` (primary), `#8e8e8e` (secondary). Font: Montserrat (Google Fonts CDN).

## Language

All content is in Portuguese (European). Keep any new content in Portuguese.


## Git Workflow
- After every code change, commit it to the current branch
- Use descriptive commit messages that explain what was changed and why
- Never switch branches or create new branches unless explicitly asked
- Run any relevant checks before committing if applicable


## Behavior
- Before starting any non-trivial task, ask clarifying questions to better 
  understand the requirements, edge cases, and expected outcome
- If a request is ambiguous, always ask rather than assume
- Confirm your understanding of the task before writing any code

## Communication
- Be concise in explanations unless asked for detail
- When something is unclear, ask don't assume
- Flag potential issues or risks even if not asked