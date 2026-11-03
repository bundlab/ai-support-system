# Contributing to AI Support System

Thank you for your interest in contributing to **AI Support System**!  
We welcome contributions from the community to help make this project better.

---

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment. Harassment, discrimination, or toxic behavior of any kind will not be tolerated.

---

## How Can I Contribute?

### Reporting Bugs
- Use the **Issues** tab
- Clearly describe the problem
- Include steps to reproduce
- Mention your Ruby version, Rails version, and OS
- Add screenshots if applicable

### Suggesting Features
- Open a new issue with the label `enhancement`
- Explain the use case and why it would be valuable
- Provide examples if possible

### Submitting Pull Requests
We love pull requests! Please follow these steps:

1. **Fork** the repository
2. Create a new branch from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Write clear and meaningful commit messages
5. Ensure your code follows the existing style
6. Test your changes thoroughly
7. Push to your fork and open a **Pull Request** against `main`

---

## Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/ai-support-system.git
cd ai-support-system

# Install dependencies
bundle install

# Setup database
rails db:create db:migrate

# Start the server
rails server
```

---

## Coding Guidelines

- Follow **Ruby Style Guide** and **Rails Best Practices**
- Prefer clear and readable code over clever code
- Write meaningful commit messages
- Keep pull requests focused (one feature/bugfix per PR)
- Add comments only when necessary
- Use Tailwind CSS classes consistently for frontend changes

---

## Pull Request Checklist

Before submitting a PR, please make sure:

- [ ] Your code runs without errors
- [ ] You have tested the changes locally
- [ ] Relevant tests pass (if applicable)
- [ ] Documentation is updated if needed
- [ ] Commit messages are clear

---

## Branch Naming Convention

- `feature/` → New features  
- `fix/` → Bug fixes  
- `docs/` → Documentation updates  
- `refactor/` → Code refactoring  
- `chore/` → Maintenance tasks  

Example:  
`feature/ai-suggested-replies`  
`fix/ticket-status-bug`

---

## Commit Message Guidelines

Use clear and descriptive messages:

```
feat: add AI auto-reply for new tickets
fix: correct SLA calculation for urgent tickets
docs: update installation instructions
refactor: improve ticket query performance
```

---

## Need Help?

Feel free to open an issue if you have questions or need guidance.

Thank you for contributing! 🚀

---

**Made with ❤️ by the AI Support System community**

---

