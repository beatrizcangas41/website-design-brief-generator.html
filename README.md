# Website Design Brief Generator

A lightweight, single-page web app for generating a strategic AI kickoff prompt for website audits, brand analysis, and design brief creation.

## Live Demo

Open the app here:

https://beatrizcangas41.github.io/website-design-brief-generator.html/website-design-brief-generator.html

## What this project does

This generator helps teams and freelancers turn a website URL and a few project inputs into a polished brief for AI-assisted design and strategy work. It can capture:

- target website URL
- brand name and business context
- primary objective and research depth
- design direction and approach
- source materials and attachments
- required deliverables
- non-negotiable elements to preserve

The result is a ready-to-use prompt that can be copied into ChatGPT, Claude, or other AI tools for a structured website audit and design brief.

## Features

- Clean, interactive form-based interface
- Optional attachment support for brand docs, screenshots, and text files
- Copy-to-clipboard prompt output
- Markdown download option
- Fully client-side implementation using HTML, CSS, and JavaScript

## Project structure

- `index.html` — redirect page to the main generator
- `website-design-brief-generator.html` — full app with interface and logic
- `README.md` — project documentation

## How to use

1. Open the live app in your browser.
2. Enter the target website URL and provide the business context.
3. Choose the research depth, creative approach, and required deliverables.
4. Add optional attachments or notes.
5. Click `Generate Prompt`.
6. Copy the generated output or download it as a `.md` file.

## Local use

Since the app is a static HTML project, you can run it locally by opening the file directly in a browser:

```bash
open website-design-brief-generator.html
```

Or serve the folder with a local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/website-design-brief-generator.html
```

## Notes

This project is intentionally lightweight and does not require a build step or external backend. It is designed for quick experimentation and reuse in design and strategy workflows.

## License

This project is shared for personal and educational use.
