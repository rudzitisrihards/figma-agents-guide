# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

A single self-contained HTML guide (`figma-agents-guide.html`) for UX designers on using AI coding agents with Figma via MCP. No build step, no dependencies, no package manager – open the file directly in a browser.

## Development

No build or install commands. To preview changes, open `figma-agents-guide.html` in a browser.

## Architecture

The entire project is one file: `figma-agents-guide.html`. It contains:
- All CSS in a `<style>` block at the top using CSS custom properties (design tokens in `:root`)
- All content as semantic HTML sections below
- No JavaScript, no external dependencies, no framework

Sections follow a consistent pattern: a `.section-label` (small caps), an `h2`, then content using reusable component classes (`.card-grid`, `.term-list`, `.step-list`, `.checklist`, `.callout`, etc.).

## Style rules

- Never use em-dashes (–). Always use en-dashes (–) instead.
- Write commit messages that describe *what changed and why*, not just what file was touched. Use a short imperative subject line followed by a blank line and 1–3 bullet points of context when the change isn't self-evident.