# System Design Case Studies

This repository contains my personal solutions to system design problems. Each case study documents how I understand and design scalable systems through requirements, assumptions, architecture diagrams, and design decisions.

## Problems Solved

| # | Problem | Solution |
|---|---|---|
| 001 | Design a URL Shortener | [View Solution](problems/001-url-shortener/README.md) |

## What Each Case Study Contains

Individual case studies may include:

- Problem statement
- Requirements and assumptions
- Architecture diagrams
- My solution
- Design decisions and trade-offs
- Editable Excalidraw files

Some sections may be added progressively as the design evolves.

## Tools

- [Excalidraw](https://excalidraw.com/) for architecture diagrams
- Markdown for documentation
- Git and GitHub for version control

## Repository Organization

```text
problems/
└── 001-url-shortener/
    ├── README.md
    └── assets/
        ├── requirements-and-assumptions.jpeg
        ├── api-and-redirect-notes.jpeg
        └── url-shortener-flow.excalidraw
```

Each problem uses a sequential numerical prefix and a lowercase kebab-case name. Its screenshots and editable diagrams belong in the problem's `assets/` directory.

## Adding a New Case Study

1. Create the next sequential directory under `problems/`, such as `002-problem-name/`.
2. Copy `templates/problem-template.md` into the new directory as `README.md`.
3. Create an `assets/` directory for screenshots and Excalidraw files.
4. Add and embed the relevant images in the problem README.
5. Add the problem to the **Problems Solved** table above.

## Learning Philosophy

These solutions reflect my understanding at the time I solve each problem. I may revise them as I learn new concepts, explore alternatives, and better understand the trade-offs involved in scalable system design.
