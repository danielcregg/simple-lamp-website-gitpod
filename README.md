# Simple LAMP Website on Gitpod

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A one-click solution for running a LAMP (Linux, Apache, MySQL, PHP) development environment on Gitpod with live reloading support.

> **Note:** This repository is a fork of [nachovz/wordpress-gitpod-one-click](https://github.com/nachovz/wordpress-gitpod-one-click).

## Overview

This project provides a pre-configured LAMP stack that runs entirely within Gitpod's cloud-based IDE. It includes Apache, MySQL, and PHP with hot-reloading powered by BrowserSync and Webpack, allowing you to develop and preview PHP websites instantly in your browser without any local setup.

## Features

- One-click Gitpod workspace launch with a full LAMP stack
- Pre-configured Apache, MySQL, and PHP environment
- Live reloading via BrowserSync and Webpack for PHP and HTML files
- Custom Gitpod Dockerfile based on the `gitpod/workspace-mysql` image
- Split-pane editor and preview layout in Gitpod

## Prerequisites

- A [Gitpod](https://gitpod.io) account (free tier available)
- A web browser

## Getting Started

### Installation

1. Fork this repository to your own GitHub account.
2. Open the repository in Gitpod by prefixing the URL with `gitpod.io/#`:
   ```
   gitpod.io/#https://github.com/YOUR-USERNAME/simple-lamp-website-gitpod
   ```
3. Gitpod will automatically build the Docker image, install dependencies, and start the server.

### Usage

1. Once the workspace loads, a preview pane will open showing the default `index.php` page.
2. Place your website files (HTML, PHP, CSS, JS) in the `public/` directory.
3. Changes to files in the `public/` directory are automatically detected, and the browser preview refreshes via BrowserSync.

## Tech Stack

| Technology | Purpose |
|---|---|
| PHP | Server-side scripting |
| Apache | Web server |
| MySQL | Database |
| Webpack | Build tooling and live reload |
| BrowserSync | Browser auto-refresh on file changes |
| Gitpod | Cloud-based development environment |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
