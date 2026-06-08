# Markdown Language Tutorial

This repository was made for studying purposes, aiming to enhance my own expertise in .md files.

Since Markdown is a very common language in documentation files and git readmes, I thought would be useful to let my studies public.

---

## Structure

### Basics
This directory contains the basics of the Markdown language. How to make a title, how to make some simple effects like bold and italic, how to put images on a .md file and how to style your markdown text a little bit.

### Intermediate
This directory contains more elaborated concepts of Markdown language like how to use external links, public apis and even "inline html" in your .md file to better organize the way your text look and some advanced structures like a ` `````` ` block and tables.

### Advanced
In this final part of the tutorial, you will learn how to use some tools of Markdown like **mermaid**, to expand the possibilities of your markdown documentations.

### Visual Structure
```mermaid
---
config:
    treeView:
        rowIndent: 20
        lineThickness: 1
    themeVariables:
        treeView:
            labelFontSize: '16px'
            labelColor: '#FFFFFF'
            lineColor: '#888888'
---
treeView-beta
    "Tutorials"
        "Basics"
            "text_basic.md"
            "basic_style.md"
            "local_links.md"
            "images.md"
        "Intermediate"
            "external_links.md"
            "public_apis.md"
            "html.md"
            "advanced_structures.md"
        "Advanced"
            "Mermaid"
                "flowchart.md"
                "class_diagram.md"
                "timeline.md"
                "mindmap.md"
                "treeview.md"
                "sequence_diagram.md"
                "state_diagram.md"
```