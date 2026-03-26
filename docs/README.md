# Project: Clint Steed Portfolio

This repository contains the professional and academic portfolio of Clint Steed, an Engineering Lecturer at Stellenbosch University.

## Technical Details

The project uses **MkDocs** to convert Markdown files into a static website.

### Prerequisites

You need Python installed. Install MkDocs and any necessary themes (e.g., Material):

```bash
pip install mkdocs mkdocs-material
```

### Build & Serve

- **Local Preview:** To serve the website locally with live-reloading:
  ```bash
  mkdocs serve
  ```
  Then, navigate to `http://127.0.0.1:8000/`.

- **Static Build:** To generate the static site (outputting to a `site/` folder):
  ```bash
  mkdocs build
  ```

## Structure

- **index.md:** The homepage of the site.
- **Academic writing/:** Papers, examples, and writing resources.
- **Blog/:** Posts on complex systems, digital mocking, etc.
- **Teaching/:** Resources and frameworks for educational research.
- **Social impact/:** Projects related to social engineering.
