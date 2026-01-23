# TheorymOS

The central content repository for Theorym's educational platform. This repository contains structured educational content across three main pillars: Learn, Solve, and Research.

## Repository Structure

```
theorymOS/
├── learn/        # Educational content organized by subject and field
│   ├── mathematics/
│   │   ├── abstract-algebra/
│   │   ├── real-analysis/
│   │   └── ...
│   ├── physics/
│   │   ├── quantum-mechanics/
│   │   ├── classical-mechanics/
│   │   └── ...
│   └── computer-science/
│       ├── algorithms/
│       ├── data-structures/
│       └── ...
├── solve/        # Problem sets and exercises
│   ├── mathematics/
│   ├── physics/
│   └── computer-science/
├── research/     # Research materials and papers
│   ├── mathematics/
│   ├── physics/
│   └── computer-science/
└── meta.json     # Metadata configuration
```

## Content Format

Content is written in MDX (Markdown with JSX) and includes frontmatter with metadata. Example:

```mdx
---
title: Introduction to Abstract Algebra
description: Fundamental concepts of abstract algebra including groups, rings, and fields

subject: mathematics
field: abstract-algebra
chapter: 1

tags: ["algebra", "groups", "rings", "fields"]
---

# Introduction to Abstract Algebra

Content goes here...
```

## Contributing

### Content Guidelines

1. **File Structure**: Place content in the appropriate subject/field directory
2. **Frontmatter**: Include required metadata (title, description, subject, field)
3. **Formatting**: Follow standard MDX formatting practices
4. **Images**: Place images in an `images` folder within the content directory
5. **Math**: Use LaTeX syntax for mathematical expressions

### Workflow

1. Fork this repository
2. Create a new branch for your changes
3. Add or modify content
4. Submit a pull request with a clear description of your changes

## Integration

This repository is designed to be integrated with the Theorym platform. Content is automatically pulled during the build process and processed using the fumadocs system.

## License

This repository is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0). This means:

- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- **NonCommercial**: You may not use the material for commercial purposes.
- **ShareAlike**: If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

For more information, see the [LICENSE](LICENSE) file.

## Contact

For questions or suggestions regarding this content repository, please contact:

- **Email**: contact@theorym.org
- **Website**: https://theorym.org
