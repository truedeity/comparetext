# Text Diff UI with JSON Formatting

This project provides a simple web-based tool for comparing two text files (especially JSON) side-by-side. It allows you to see the differences between the source and target texts and highlights insertions, deletions, and unchanged content.

## Features
- **Side-by-side comparison**: View source and target texts next to each other.
- **Diff highlighting**: Highlights differences (insertions in green, deletions in red with strikethrough).
- **Auto-format JSON**: If JSON is pasted into the text areas, it is auto-formatted for better readability.
- **Customizable UI**: The tool uses flexible layouts, making it easy to adjust.

## Prerequisites
To run this tool locally, you'll need the following:
- A modern web browser (Chrome, Firefox, etc.).
- **Optional**: Internet access to fetch the necessary JavaScript libraries via CDN or download the libraries locally as described below.

## Installation

### 1. Download the Files

Necessary files for the project:
- `index.html`: The main HTML file.
- `diff.min.js`: The `jsdiff` JavaScript library for diff comparison.
