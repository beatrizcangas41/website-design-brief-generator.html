# Website Design Brief Generator

<div align="center">

![HTML](https://img.shields.io/badge/HTML-5-orange?style=for-the-badge&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)
![Static App](https://img.shields.io/badge/Type-Static%20Web%20App-18181b?style=for-the-badge)

</div>

A sleek, single-page generator that turns a website URL and a few project inputs into a polished AI kickoff prompt for website audits, brand strategy, and design brief creation.

## Live Demo

Visit the app here:

https://beatrizcangas41.github.io/website-design-brief-generator.html/website-design-brief-generator.html

## Overview

This project was designed to make website analysis faster and more structured. Instead of manually creating a long brief from scratch, you can enter:

- the target website URL
- business goals and context
- preferred creative direction
- research depth
- required deliverables
- key constraints and preservation notes
- optional supporting files and brand assets

The app then generates a ready-to-use prompt for AI tools such as ChatGPT, Claude, or other design/strategy assistants.

## Why it stands out

- clean and intuitive UI
- guided workflow for input collection
- ready-to-copy prompt output
- export as Markdown
- no backend or setup complexity
- works as a static HTML project

## Features

### ✨ Smart prompt generation
Generate a structured, evidence-based kickoff brief tailored to the project.

### 🧠 Strategic project inputs
Capture brand context, research depth, design direction, competitors, and constraints.

### 📎 Attachment support
Add supporting docs such as brand guidelines, reports, and design references.

### 📤 Copy and export
Copy the generated prompt directly to the clipboard or download it as a `.md` file.

### ⚡ Lightweight and fast
Everything runs directly in the browser with no build step required.

## Project Structure

```text
website-design-brief-generator.html/
├── index.html                  # redirect page to the main app
├── website-design-brief-generator.html  # main interactive interface and app logic
├── README.md                   # project documentation
└── .gitignore                  # repository configuration (if present)
```

## How to Use

1. Open the live demo in your browser.
2. Enter the website URL.
3. Fill in the project context, goals, and deliverables.
4. Add any relevant brand references or attached files.
5. Click `Generate Prompt`.
6. Copy the result or download it as Markdown.

## Local Development

Because this is a static site, you can run it locally without any framework or build process.

### Option 1: Open directly

```bash
open website-design-brief-generator.html
```

### Option 2: Serve locally

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/website-design-brief-generator.html
```

## Use Cases

This app is useful for:

- agency website audits
- brand refresh planning
- UX review prep
- design brief creation
- content and strategy workshops
- AI-assisted creative kickoff sessions

## Notes

This project is intentionally lightweight and designed for fast experimentation and practical use. It keeps the experience simple while still producing high-value strategic output.

## License

This project is intended for personal and educational use.

---

Made with a focus on clean design, practical workflow, and AI-powered creative planning.
