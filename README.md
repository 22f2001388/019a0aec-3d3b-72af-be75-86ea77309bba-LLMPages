# LLMPages

A static website designed to publish a collection of specific files via GitHub Pages.

## Overview

LLMPages serves as a repository for a curated set of static assets, including text, JSON, SVG, and markdown files. The project demonstrates content compliance and integrity through specific file requirements and is deployed using GitHub Pages for public accessibility. The `index.html` file provides a central directory to all hosted assets.

## Features

- Generates nine required static files (TXT, JSON, MD, SVG, HTML, LICENSE) with specific content.
- Provides a central `index.html` homepage that links to and describes all other assets.
- Configured for direct deployment as a public static site using GitHub Pages.
- Includes a content integrity check via a unique identifier file (`uid.txt`).
- Ensures content compliance with predefined constraints, such as word count and JSON schema.

## Technology Stack

- HTML5
- CSS3
- JSON
- SVG
- GitHub Pages

## Getting Started

### Prerequisites

A modern web browser is required to view the deployed site.

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/llmpages.git
    ```

2.  Navigate to the project directory:
    ```bash
    cd llmpages
    ```

3.  Open `index.html` in your web browser to view the site locally.

## Usage

### Accessing the Deployed Site

The site is accessible via its GitHub Pages URL:

`https://your-username.github.io/llmpages/`

### Accessing Individual Assets

Individual files can be accessed directly from the deployed site. For example, to retrieve the restaurant data:

```bash
# Using curl to fetch the JSON data
curl https://your-username.github.io/llmpages/restaurant.json
```

The `index.html` page provides direct links to all assets.

## Project Structure

```plaintext
/
├── .gitignore
├── LICENSE
├── about.md
├── ashravan.txt
├── dilemma.json
├── index.html
├── pelican.svg
├── prediction.json
├── restaurant.json
└── uid.txt
```

-   `.gitignore`: Specifies intentionally untracked files to ignore.
-   `LICENSE`: Contains the MIT License for the project.
-   `about.md`: A markdown file with exactly three words.
-   `ashravan.txt`: A short story (300-400 words).
-   `dilemma.json`: JSON data describing two ethical scenarios.
-   `index.html`: The main entry point and homepage.
-   `pelican.svg`: A simple SVG icon of a pelican.
-   `prediction.json`: JSON data containing a financial forecast.
-   `restaurant.json`: JSON data for a restaurant recommendation.
-   `uid.txt`: Contains a mandatory 75-digit unique identifier.

## License

This project is licensed under the MIT License.