# Contributing to TheorymOS

Thank you for your interest in contributing to theorymOS! This document provides guidelines and instructions for contributing content to this repository.

## Content Structure

All content should be placed in the appropriate directory based on its category:

- `/learn/` - Educational content organized by subject and field
- `/solve/` - Problem sets and exercises
- `/research/` - Research materials and papers

Within each category, content should be organized by subject (e.g., mathematics, physics, computer science) and then by field within that subject.

## File Format

Content should be written in MDX (Markdown with JSX) format. Each file should include frontmatter with metadata at the top of the file.

### Required Frontmatter Fields

```yaml
---
title: "Title of the Content"
description: "Brief description of the content"
subject: "Subject area (e.g., mathematics, physics)"
field: "Field within the subject (e.g., abstract-algebra, quantum-mechanics)"
---
```

### Recommended Frontmatter Fields

```yaml
---
date: "YYYY-MM-DD"                   # Date of creation
lastModified: "YYYY-MM-DD"           # Date of last modification
chapter: 1                           # Chapter number (if applicable)
section: "Section name"              # Section name (if applicable)
tags: ["tag1", "tag2"]               # Content tags for categorization
references:                        # List of contributors
  - id: "1"
    username: "username"
    displayName: "Display Name"
    avatar: "https://github.com/username.png"
    contributions: 10
    contributionType: "author|editor|reviewer|transcriber|annotator"
    lastContribution: "YYYY-MM-DD"
    githubUrl: "https://github.com/username"
---
```

## Content Guidelines

### General Guidelines

1. **Accuracy**: Ensure all information is accurate and up-to-date.
2. **Clarity**: Write in clear, concise language appropriate for the target audience.
3. **Completeness**: Cover the topic comprehensively within the scope of the content.
4. **Consistency**: Maintain consistent terminology, notation, and style throughout.

### Formatting Guidelines

1. **Headings**: Use appropriate heading levels (# for title, ## for sections, etc.).
2. **Lists**: Use bulleted lists for unordered items and numbered lists for sequential items.
3. **Code Blocks**: Use triple backticks for code blocks with language specification.
4. **Images**: Place images in an `images` folder within the content directory and reference them using relative paths.
5. **Links**: Use relative links for internal content and full URLs for external resources.

### Mathematical Content

1. **LaTeX**: Use LaTeX syntax for mathematical expressions.
2. **Inline Math**: Use `$...$` for inline math.
3. **Display Math**: Use `$$...$$` for display math.
4. **Theorems and Proofs**: Use consistent formatting for theorems, lemmas, proofs, etc.

Example:
```mdx
The quadratic formula $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$ is used to solve equations of the form:

$$ax^2 + bx + c = 0$$

where $a \neq 0$.
```

## Submission Process

1. **Fork the Repository**: Create your own fork of the repository.
2. **Create a Branch**: Create a new branch for your changes.
3. **Make Changes**: Add or modify content following the guidelines above.
4. **Test**: Ensure your content renders correctly in a local environment if possible.
5. **Submit a Pull Request**: Submit a pull request with a clear description of your changes.

## Review Process

All submissions will be reviewed for:

1. **Content Quality**: Accuracy, clarity, and completeness
2. **Formatting**: Adherence to formatting guidelines
3. **Metadata**: Completeness and accuracy of frontmatter
4. **Integration**: Compatibility with the existing content structure

## Code of Conduct

Please be respectful and constructive in all interactions. We aim to create a welcoming and inclusive community for all contributors.

## Questions?

If you have any questions or need assistance, please contact us at contact@theorym.org or open an issue in the repository.

Thank you for contributing to theorymOS! 