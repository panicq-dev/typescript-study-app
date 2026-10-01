# NoteZ

## Overview

NoteZ is a mobile application built with TypeScript, React Native, and Expo that transforms images into personalized study materials through Artificial Intelligence.

Users can capture a photo of handwritten notes, textbooks, presentations, articles, or any educational content and instantly convert it into summaries, exercises, or flashcards.

The application combines Optical Character Recognition (OCR) technology with advanced AI models, enabling automated content extraction and personalized study material generation.

---

## Problem Statement

Creating high-quality study materials is often a time-consuming process. Students and professionals spend significant amounts of time organizing notes, writing summaries, creating flashcards, and preparing exercises before beginning the actual learning process.

NoteZ simplifies this workflow by automating content extraction and study material generation, allowing users to focus on learning rather than content preparation.

---

## Features

### OCR-Based Text Recognition

Extract textual content from images captured through the device camera or selected from the gallery.

Supported sources include:

- Handwritten notes
- Books and textbooks
- Academic articles
- Presentation slides
- Printed documents
- Study guides

### AI-Powered Content Generation

Leverage Gemini and Grok APIs to generate learning materials automatically from extracted content.

#### Summaries

Generate concise or detailed summaries focused on key concepts and essential information.

#### Exercises

Create practice questions, knowledge assessments, and study activities based on the captured content.

#### Flashcards

Generate question-and-answer flashcards optimized for active recall and revision.

### Personalized Learning Experience

Adapt generated content according to:

- Study objectives
- Knowledge level
- Subject complexity
- Preferred study format

---

## Architecture

```text
User
 │
 ▼
Image Capture
 │
 ▼
OCR Processing
 │
 ▼
Text Extraction
 │
 ├── Gemini API
 │
 └── Grok API
         │
         ▼
AI Processing
         │
         ▼
Generated Content
         │
         ├── Summaries
         ├── Exercises
         └── Flashcards
```

---

## Technology Stack

### Mobile Development

- React Native
- Expo
- TypeScript

### Artificial Intelligence

- Gemini API
- Grok API

### Content Recognition

- OCR (Optical Character Recognition)

### Runtime Environment

- Node.js

