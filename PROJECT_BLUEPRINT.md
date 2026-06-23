# Project Blueprint

## Project Name

line-chat-image-maker

## Purpose

A simple browser-only tool for teachers to create LINE-style chat images for worksheets, handouts, quizzes, and exams.

The output is designed for black-and-white printing. It focuses on readable text, clear contrast, and simple classroom-friendly visuals.

## Core Principles

- No generative AI
- No AI API integration
- No external service dependency during use
- Works by opening `index.html` in a browser
- Printable in black and white
- Easy for non-technical users to edit

## Current Features

- Create multiple chat roles
- Choose left, right, or right-without-avatar message placement
- Use either a custom avatar character or a PNG avatar from the built-in avatar library
- Edit message text and optional time labels
- Preview the chat image instantly
- Export PNG
- Export SVG
- Print or save as PDF through the browser
- Choose several output widths, including a very narrow layout

## File Structure

- `index.html`: main interface
- `styles.css`: visual layout and print styling
- `app.js`: editor behavior, preview rendering, and export logic
- `*.png`: avatar image library
- `README.md`: short project introduction
- `.gitignore`: ignored local files

## Intended Users

- Teachers
- Tutors
- Worksheet creators
- Exam designers
- Educational content creators

## Suggested Next Steps

1. Add message reordering controls.
2. Add save/load project data as JSON.
3. Add one-click duplicate message and duplicate role actions.
4. Add A4 print layout presets.
5. Add avatar preview thumbnails in the selector.
6. Add a sample conversation library for classroom scenarios.

## Deployment Options

This project can be hosted with GitHub Pages because it is a static website.

Recommended repository name:

`line-chat-image-maker`
