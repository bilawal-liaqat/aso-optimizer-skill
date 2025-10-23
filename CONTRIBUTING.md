# Contributing to ASO Optimizer

First off, thanks for taking the time to contribute! 🎉

This document provides guidelines for contributing to the ASO Optimizer skill. Following these guidelines helps maintain quality and makes the contribution process smooth for everyone.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Setup](#development-setup)
- [Skill Structure](#skill-structure)
- [Submitting Changes](#submitting-changes)
- [Style Guidelines](#style-guidelines)

## Code of Conduct

This project and everyone participating in it is governed by respect and professionalism. Be kind, be respectful, and help create a welcoming environment.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates.

When creating a bug report, include:
- **Clear title and description**
- **Steps to reproduce** the issue
- **Expected vs actual behavior**
- **Claude version** you're using
- **Example app description** that triggered the issue (if applicable)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:
- **Clear title and description**
- **Use case**: Why would this be useful?
- **Proposed solution**: How should it work?
- **Alternatives considered**: What other approaches did you think about?

### Contributing Code

#### Types of Contributions

1. **Bug Fixes**: Fix issues in keyword generation, metadata optimization, etc.
2. **New Features**: Add new ASO capabilities or workflows
3. **Documentation**: Improve README, reference files, or code comments
4. **Examples**: Add new use case examples or templates
5. **Translations**: Add support for new language markets

## Development Setup

### Prerequisites

- Python 3.7+ (for packaging script)
- Access to Claude.ai with custom skills
- Text editor (VS Code, Sublime, etc.)

### Getting Started

1. **Fork the repository**
   ```bash
   git clone https://github.com/yourusername/aso-optimizer-skill.git
   cd aso-optimizer-skill
   ```

2. **Make your changes**
   - Edit files in the appropriate directories
   - Follow the skill structure guidelines below

3. **Test your changes**
   - Package the skill: `python3 scripts/package_skill.py ./aso-optimizer`
   - Upload to Claude and test thoroughly
   - Try multiple scenarios and edge cases

4. **Document your changes**
   - Update README.md if needed
   - Add comments to complex logic
   - Update reference files if relevant

## Skill Structure

```
aso-optimizer/
├── SKILL.md                    # Main orchestration - workflow logic
├── references/
│   ├── store-guidelines.md     # Platform-specific rules
│   ├── keyword-strategies.md   # Research methodologies
│   └── competitor-analysis.md  # Analysis frameworks
├── README.md                   # User-facing documentation
├── LICENSE                     # MIT License
└── .gitignore                  # Git ignore rules
```

### File Purposes

**SKILL.md**
- Main workflow and decision logic
- When to use each reference file
- Integration with other Claude tools
- Keep under 500 lines when possible

**Reference Files**
- Detailed methodologies and best practices
- Loaded on-demand by Claude
- Can be longer and more comprehensive
- Should be self-contained

**README.md**
- User-facing installation and usage guide
- Should be accessible to non-technical users
- Include examples and troubleshooting

## Submitting Changes

### Pull Request Process

1. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/bug-description
   ```

2. **Make your changes**
   - Follow the style guidelines below
   - Write clear commit messages
   - Keep commits focused and atomic

3. **Test thoroughly**
   - Test the packaged skill in Claude
   - Try edge cases and error scenarios
   - Verify character limits still work
   - Check that nothing broke existing features

4. **Update documentation**
   - Update README.md if user-facing changes
   - Update SKILL.md if workflow changes
   - Add inline comments for complex logic

5. **Submit pull request**
   - Clear title describing the change
   - Detailed description of what and why
   - Reference any related issues
   - Include screenshots/examples if applicable

### Commit Message Guidelines

Use clear, descriptive commit messages:

```
Good:
- "Add support for keyword density analysis"
- "Fix character count validation for Android"
- "Update competitor analysis framework for 2025"

Bad:
- "Fix bug"
- "Update stuff"
- "WIP"
```

Format: `<type>: <description>`

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `refactor`: Code restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

## Style Guidelines

### SKILL.md Writing Style

- **Use imperative form**: "Generate keywords" not "Generates keywords"
- **Be concise**: Every word should add value
- **Structure clearly**: Use headers, bullets, and sections
- **Provide context**: Explain the "why" not just the "what"

### Reference Files

- **Be comprehensive**: These can be longer and more detailed
- **Use examples**: Show, don't just tell
- **Organize logically**: Group related information
- **Keep current**: Update with latest ASO best practices

### Code (if applicable)

- Follow PEP 8 for Python scripts
- Add docstrings to functions
- Keep functions focused and small
- Use meaningful variable names

### Documentation

- Use clear, simple English
- Avoid jargon where possible
- Include code examples with context
- Keep examples realistic and practical

## Testing Guidelines

Before submitting, test your changes with:

### Variety of Apps
- Photo editing apps
- Productivity apps
- Games
- Finance apps
- Health & fitness apps

### Platforms
- iOS only
- Android only
- Both platforms

### Languages
- English
- Non-English single language
- Multiple languages

### Workflows
- Complete ASO from scratch
- Competitor analysis only
- Keyword refresh
- Localization

### Edge Cases
- Very short app descriptions
- Complex multi-feature apps
- Niche categories
- International markets

## Questions?

- **Open an issue**: For discussions or clarifications
- **Check existing issues**: Your question might already be answered
- **Be patient**: Maintainers are volunteers

## Recognition

All contributors will be recognized in the project. Your contributions make this tool better for the entire indie developer community!

Thank you for contributing! 🙏
