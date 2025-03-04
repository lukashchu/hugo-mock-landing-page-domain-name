# Opus Landing Page

A mock landing page for **Opus**, a revolutionary crowdsourcing platform that leverages AI and automation to deliver higher-quality, faster responses compared to traditional platforms like Amazon Mechanical Turk.

## Overview

This repository contains the source code for the Opus landing page, built with [Hugo](https://gohugo.io/). The site showcases key features of Opus—such as higher payouts, faster response times, and gamified incentives—while emphasizing how Opus is reshaping the crowdsourcing landscape. All of this was created as a part of my course work for CIS 3500: Software Design/Engineering with Professor Lumbroso at the University of Pennsylvania

## Description of Workflow Created

This repository uses GitHub Actions to automate the building and deployment of the Opus landing page to GitHub Pages. The workflow is triggered whenever changes are pushed to the main branch, ensuring that the published website always reflects the latest updates.

### Workflow Details:

- **Name**: 🏗️ Build and Deploy GitHub Pages
- **Trigger**: Pushes to the main branch
- **Environment**: Ubuntu 22.04
- **Key Steps**:
  1. Checks out the repository code with submodules (for Hugo themes)
  2. Sets up Hugo environment (version 0.144.1, extended edition)
  3. Compiles the static website files with optimization flags
  4. Publishes the built site to the gh-pages branch

This automation simplifies the deployment process, eliminating the need for manual builds and deployments. With this workflow in place, any team member can contribute content updates by simply pushing changes to the main branch, and the website will automatically rebuild and publish.

### Technical Note:
The workflow includes commented code for custom domain configuration, which can be uncommented if the site needs to be published to a custom domain in the future.

## Features

- **Higher Payouts:** Earn more compared to other crowdsourcing platforms.
- **Faster Responses:** Get survey responses quickly with our streamlined system.
- **AI-Driven Quality:** Enjoy improved data quality thanks to intelligent quality control.
- **Increased Engagement:** Benefit from an engaging, gamified experience.
- **Lower Costs:** Launch surveys with minimal startup investment.
- **Automation & AI:** Experience smarter workflows and automated processes.

## User Stories

The project is guided by user stories that follow the INVEST criteria, ensuring each feature is:
- **Independent**
- **Negotiable**
- **Valuable**
- **Estimable**
- **Small**
- **Testable**

Examples include:
- As a user answering surveys, I want to earn more than on platforms like Amazon mTurk.
- As a requester posting surveys, I want to receive responses faster than on other platforms.
- As a responder, I want an engaging experience that motivates me to participate regularly.
- *(See [USER-STORIES.md](USER-STORIES.md) for a complete list.)*

## Technologies

- **Hugo:** Fast, modern static site generator.
- **Markdown:** Content management through Markdown files.
- **CSS & JavaScript:** For styling and interactive elements.
