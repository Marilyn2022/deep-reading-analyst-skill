# Contributing to Deep Reading Analyst

First off, thank you for considering contributing to Deep Reading Analyst! 🎉

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When creating a bug report, include:

- **Clear title and description**
- **Steps to reproduce** the issue
- **Expected behavior** vs. **actual behavior**
- **Claude version** and platform (Desktop/Web)
- **Screenshots** if applicable

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion:

- **Use a clear and descriptive title**
- **Provide detailed description** of the suggested enhancement
- **Explain why** this enhancement would be useful
- **Provide examples** of how it would work

### Pull Requests

1. **Fork** the repository
2. **Create a branch** for your feature (`git checkout -b feature/AmazingFeature`)
3. **Make your changes**
4. **Test thoroughly** - ensure the skill works as expected
5. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
6. **Push** to the branch (`git push origin feature/AmazingFeature`)
7. **Open a Pull Request**

## Development Guidelines

### Skill Structure

When modifying the skill, maintain this structure:

```
deep-reading-analyst/
├── SKILL.md (main workflow)
└── references/ (detailed frameworks)
```

### Writing Style

- **Be concise** - Context window is a shared resource
- **Use examples** - Concrete examples over abstract explanations
- **Test everything** - Verify changes work in actual Claude conversations
- **Document** - Update relevant documentation

### Adding New Frameworks

If you're adding a new thinking framework:

1. Create a new `.md` file in `references/`
2. Follow the template structure of existing frameworks
3. Include:
   - **Overview** - What is this framework?
   - **When to use** - Specific scenarios
   - **How to use** - Step-by-step process
   - **Examples** - Concrete applications
   - **Common mistakes** - What to avoid
4. Reference it in `SKILL.md`
5. Update README with the new framework

### Adding Output Templates

New output templates should:

1. Be added to `references/output_templates.md`
2. Include clear structure and examples
3. Specify when to use this template
4. Be practical and actionable

## Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring community for all.

### Our Standards

**Positive behavior includes:**
- Being respectful and inclusive
- Gracefully accepting constructive criticism
- Focusing on what's best for the community
- Showing empathy towards others

**Unacceptable behavior includes:**
- Harassment or discriminatory language
- Trolling or insulting comments
- Public or private harassment
- Publishing others' private information

## Testing Your Changes

Before submitting a pull request:

1. **Package the skill** using the skill creator tools
2. **Import** the skill into Claude
3. **Test** with various types of content:
   - Short articles
   - Long papers
   - Different analysis depths
   - Different output formats
4. **Verify** all references load correctly
5. **Check** that existing functionality still works

## Commit Message Guidelines

Use clear and meaningful commit messages:

- **feat:** New feature
- **fix:** Bug fix
- **docs:** Documentation changes
- **refactor:** Code refactoring
- **test:** Adding tests
- **chore:** Maintenance tasks

Examples:
```
feat: add comparative analysis framework
fix: correct typo in systems thinking reference
docs: update usage guide with new examples
```

## Questions?

Feel free to:
- Open an issue with the "question" label
- Start a discussion in GitHub Discussions
- Reach out to maintainers

## Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

Thank you for contributing! 🙌
