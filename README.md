# WebTech Static Pages Collection

A simple collection of static web pages, showcasing basic HTML structures and content.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit](https://img.shields.io/github/last-commit/ChiragBorse/webtech)](https://github.com/ChiragBorse/webtech/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/ChiragBorse/webtech)](https://github.com/ChiragBorse/webtech)

## Overview

This repository hosts a small collection of static HTML pages. Each file represents a standalone web page, designed to be simple, direct, and easily viewable in any web browser. This project serves as a basic demonstration of HTML file organization and content delivery.

**Key Value Proposition:** Provides straightforward, accessible web content without complex server-side logic or client-side scripting. Ideal for quick information display or as a starting point for learning web development.

**Target Audience:** Anyone interested in viewing simple web pages, or beginners looking at basic HTML project structures.

**Current Status:** Initial release, containing a few distinct static pages.

## Features

This collection currently includes the following static pages:

*   **`INDIA.HTML`**: A dedicated page likely containing information, facts, or a presentation related to India.
*   **`chirag.html`**: A personal page, potentially a resume, portfolio, or contact information for Chirag.
*   **`ruus.html`**: Another distinct static page, with content specific to its topic (details inferred from content).

Each page is:
*   **Static**: Content is fixed and delivered directly from the HTML file.
*   **Browser-Agnostic**: Designed to render correctly across various modern web browsers.
*   **Self-Contained**: Each page functions independently without relying on external scripts or complex dependencies within this repository.

## Tech Stack

This project is built using fundamental web technologies:

*   **HTML5**: The core language for structuring and presenting content on the web.

There are no external frameworks, libraries, or complex dependencies involved, ensuring maximum simplicity and compatibility.

## Architecture

The project employs a very simple, flat file architecture:

```
.
├── INDIA.HTML
├── chirag.html
└── ruus.html
```

Each `.html` file is a self-contained web page. There are no subdirectories for assets (like CSS, JavaScript, or images) within this structure, implying that any styling or scripting would either be inline or linked from external CDNs.

## Getting Started

To view and interact with these static web pages, you only need a web browser.

### Prerequisites

*   **Web Browser**: Any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

### Installation

No complex installation is required. Simply clone the repository to your local machine.

```bash
git clone https://github.com/ChiragBorse/webtech.git
cd webtech
```

### Configuration

No configuration files or environment variables are needed. The pages are ready to be viewed directly.

## Usage

To open and view any of the web pages:

1.  **Navigate to the project directory** in your file explorer or terminal.
2.  **Double-click** on any of the `.html` files (e.g., `INDIA.HTML`, `chirag.html`, `ruus.html`). Your default web browser will open the page.

Alternatively, from your terminal:

```bash
# On macOS
open INDIA.HTML

# On Windows
start INDIA.HTML

# On Linux (using xdg-open, common for most desktop environments)
xdg-open INDIA.HTML
```

Repeat this for `chirag.html` and `ruus.html` to view the other pages.

## Development

Developing with this project is straightforward, as it consists solely of HTML files.

### Setting Up Development Environment

1.  **Text Editor**: Use any text editor (e.g., VS Code, Sublime Text, Atom) to open and modify the `.html` files.
2.  **Browser**: Keep a web browser open to refresh and see your changes instantly.

### Code Style Guidelines

*   **HTML5 Standard**: Adhere to modern HTML5 best practices.
*   **Indentation**: Use 2 or 4 spaces for indentation for readability.
*   **Semantic HTML**: Use appropriate semantic tags (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`) where applicable, even in simple pages.

## Deployment

Deploying these static pages is very simple and can be done on any static web hosting service.

1.  **Upload Files**: Copy the entire contents of the `webtech` directory (specifically the `.html` files) to your web server's root directory.
2.  **Static Hosting**: Services like GitHub Pages, Netlify, Vercel, or even a simple Apache/Nginx server can host these files directly.
    *   **GitHub Pages**: Push your code to a GitHub repository and enable GitHub Pages in the repository settings. The pages will be accessible at `https://your-username.github.io/webtech/`.

## Contributing

Contributions are welcome! If you have suggestions for improving existing pages, adding new simple static pages, or enhancing the documentation, please follow these steps:

1.  **Fork the repository**.
2.  **Create a new branch** for your feature or bug fix: `git checkout -b feature/your-feature-name`.
3.  **Make your changes** and commit them with clear, descriptive messages.
4.  **Push your branch** to your forked repository.
5.  **Open a Pull Request** to the `main` branch of this repository.

Please ensure your code adheres to the existing style and quality standards.

## Troubleshooting

*   **Page not loading**:
    *   Ensure the `.html` file exists in the directory you are trying to open.
    *   Check if your browser is displaying any error messages.
*   **Content not displaying correctly**:
    *   Verify the HTML structure for any syntax errors (e.g., unclosed tags).
    *   If external CSS/JS were added, ensure their links are correct and accessible.

## Roadmap

*   Introduce basic CSS styling for improved aesthetics.
*   Add more diverse content to existing pages.
*   Explore adding simple JavaScript for minor interactivity.

## License & Credits

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

**Credits:**

*   **Chirag Borse** - Initial Creator and Maintainer.