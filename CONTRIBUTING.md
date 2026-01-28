# Contributing to Library of Wisdom

**Created by: The Navigator (Member 1)**

Welcome to the Library of Wisdom—a Markdown-based digital encyclopedia! This document outlines the rules and guidelines for contributing to this collaborative learning project.

## 🎯 Project Purpose

This repository is a hands-on learning activity designed to teach:
- Git branching and merging workflows
- Pull Request (PR) best practices
- Code review processes
- Merge conflict resolution
- Professional collaborative development

## 🚫 Golden Rule

**NO DIRECT PUSHES TO `main` BRANCH**

All changes must go through the Pull Request (PR) process. This applies to everyone, including the repository Lead.

**Why?** This simulates real-world development environments where code changes require review and approval before being integrated into the main codebase.

## 🔄 Contribution Workflow

### 1. Create a Branch

Always create a new branch for your work:

```bash
git checkout -b feature/your-feature-name
```

**Branch Naming Convention for This Activity:**
- `feature/aguilan` - Your personal feature branch for this activity

**Examples:**
- `feature/aguilan` - Member 1 (Navigator)
- `feature/aguilar` - Member 2 (Historian)
- `feature/alicon` - Member 3 (Stylist)
- `feature/aguilar j` - Member 4 (Coder)
- `feature/abalos` - Member 5 (Editor)

**General Conventions (for future reference):**
- `feature/description` - For new features or additions
- `fix/description` - For bug fixes
- `docs/description` - For documentation updates
- `refactor/description` - For code refactoring

### 2. Make Your Changes

- Write clear, descriptive commit messages
- Keep commits focused and atomic
- Test your changes before committing

### 3. Commit Your Work

```bash
git add .
git commit -m "Clear description of what you changed"
```

**Commit Message Guidelines:**
- Use present tense ("Add feature" not "Added feature")
- Be descriptive but concise
- Reference issue numbers if applicable (e.g., "Fix #123: Description")

### 4. Push Your Branch

```bash
git push origin feature/your-feature-name
```

### 5. Create a Pull Request

1. Go to the repository on GitHub
2. Click "New Pull Request"
3. Select your branch
4. Fill in the PR template:
   - **Title:** Clear, descriptive title
   - **Description:** What changes did you make and why?
   - **Testing:** How did you test your changes?
5. Request review from at least one team member
6. Link any related issues

### 6. Code Review

- At least **1 approval** is required before merging
- Address all review comments
- Keep discussions professional and constructive
- Make requested changes in new commits (don't force push)

### 7. Merge

Once approved:
- The PR author or a team member can merge
- Delete the branch after merging (keep the repo clean)

## 📝 Pull Request Requirements

Your PR should include:

- [ ] Clear description of changes
- [ ] All commits have meaningful messages
- [ ] Code follows project conventions
- [ ] No conflicts with `main` branch
- [ ] At least one approval from a team member

## 🤝 Code Review Guidelines

**As a Reviewer:**
- Review PRs promptly (within 24-48 hours)
- Provide constructive feedback
- Approve if changes look good, request changes if needed
- Use GitHub's review features (Approve, Request Changes, Comment)

**As an Author:**
- Respond to feedback professionally
- Make requested changes promptly
- Ask questions if feedback is unclear
- Thank reviewers for their time

## ✅ Best Practices

1. **Pull Before You Start:** Always pull the latest changes before creating a new branch
   ```bash
   git checkout main
   git pull origin main
   git checkout -b feature/your-feature
   ```

2. **Keep PRs Small:** Smaller PRs are easier to review and less likely to have conflicts

3. **Update Regularly:** Keep your branch up to date with `main`
   ```bash
   git checkout main
   git pull origin main
   git checkout feature/your-feature
   git merge main
   ```

4. **Communicate:** Use PR descriptions and comments to explain your approach

5. **Be Respectful:** We're all learning together. Be kind in code reviews.

## 🚨 What NOT to Do

- ❌ Don't push directly to `main`
- ❌ Don't merge your own PR without approval
- ❌ Don't force push to shared branches
- ❌ Don't commit sensitive information (passwords, API keys, etc.)
- ❌ Don't merge PRs with unresolved conflicts
- ❌ Don't leave PRs unreviewed for extended periods

## 🆘 Getting Help

If you're stuck or have questions:
- Ask in the team chat or communication channel
- Tag team members in your PR comments
- Create a GitHub issue for discussion

## 📚 Resources

- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)
- [How to Write Good Commit Messages](https://chris.beams.io/posts/git-commit/)
- [Code Review Best Practices](https://github.com/google/eng-practices/blob/master/review/reviewer/standard.md)

---

**Remember:** Every contribution, no matter how small, is valuable. Let's build something great together! 🚀
