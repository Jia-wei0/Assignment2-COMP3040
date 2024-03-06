# Hosting Your Resume on GitHub Pages


## Contents

- [Purpose](#Purpose)
- [Prerequisites](#Prerequisites)
- [Instructions](#Instructions)
- [More Resources](#More-Resources)
- [Authors and Acknowledgements](#Authors-and-Acknowledgements)
- [FAQs](#FAQs)
  - [Why is Markdown better than a word processor for documentation?](#Why-is-Markdown-better-than-a-word-processor-for-documentation)
  - Why is my resume not showing up on GitHub Pages?



## Purpose

This README help you through hosting and formatting your resume on GitHub Pages, demonstrating practical application of the principles of current Technical Writing as explained in Andrew Etter's *Modern Technical Writing*. We aim to relate each step of the process to Etter's recommendations for technical documentation, with a focus on using lightweight markup (Markdown), distributed version control (GitHub), and static site generators.


## Prerequisites

- A resume formatted in Markdown. If you're unfamiliar with Markdown, don't worry! It's a simple, readable syntax for formatting text. And I've prepared a [link](#More-Resources) to the *Markdown Guide* in the More Resource section.
- A GitHub account.


## Instructions

### 1. Create a GitHub Repository

**Etter's Principle**:```Use distributed version control systems.```

**Practical Step**: Sign into your GitHub account and create a new repository named `<yourusername>.github.io`, replacing `<yourusername>` with your GitHub username. This will host your static site (your resume) on GitHub Pages.

### 2. Add Your Resume in Markdown Format

**Etter's Principle**: Write using lightweight markup languages.

**Practical Step**: Create a file named `index.md` in your repository and paste your Markdown-formatted resume into this file. Markdown allows you to format your document in a way that's both human-readable and convertible into HTML.

### 3. Enable GitHub Pages for Your Repository

**Etter's Principle**: Use static site generators.

**Practical Step**: In your repository settings, find the GitHub Pages section and select the main branch as the source. GitHub will automatically render your Markdown file into a static website using Jekyll, a static site generator.

### 4. Customize Your Page (Optional)

**Etter's Principle**: Emphasize simplicity and usability in design.

**Practical Step**: You can customize the look of your resume by adding a Jekyll theme or editing the CSS directly. This step is optional but helps make your resume visually appealing.

### 5. Update and Maintain Your Resume

**Etter's Principle**: Keep documentation current.

**Practical Step**: Whenever you need to update your resume, simply commit changes to the `index.md` file in your repository. GitHub Pages will automatically rebuild your site with the changes.


## Animated GIF Demo

Include an animated gif showing the process of editing, committing, and viewing changes to your resume on GitHub Pages. Ensure your own name is visible in the resume demo.


## More Resources

- **Markdown Guide**: For those new to Markdown, [Markdown Guide](https://www.markdownguide.org/getting-started/) is an excellent place to start.
- **Modern Technical Writing**: Andrew Etter's book for a deeper understanding of the principles applied here.
- **GitHub Pages Documentation**: For more details on using GitHub Pages.
- **Jekyll**: Learn more about the static site generator used by GitHub Pages.


## Authors and Acknowledgements

Credit to Andrew Etter for the principles outlined in *Modern Technical Writing* and to GitHub for providing the platform used in this tutorial. This README was prepared by [Your Name], with thanks to all template authors and group members who contributed.


## FAQs

### Why is Markdown better than a word processor for documentation?

Markdown is preferred for its simplicity, readability, and ease of conversion into HTML or other formats. It allows writers to focus on content rather than formatting and is universally compatible across different platforms and editors.

### Why is my resume not showing up on GitHub Pages?

Ensure you've named your repository `<yourusername>.github.io` and that your resume is in the `index.md` file. Also, check if GitHub Pages is enabled in your repository settings. It may take a few minutes for changes to go live, so be patient.
