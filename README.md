# 📦 GitHub Templates

A collection of reusable GitHub repository templates including issue forms, pull request templates, contribution guidelines, and more.

This repository aims to provide standardized `.github/` files that can be used across multiple repositories to ensure consistency and reduce setup effort.

## 🧰 Available Templates

- **Issue Templates** (`.github/ISSUE_TEMPLATE/`)
  - Bug report (`bug.yml`, `bug.md`)
  - Feature request (`feature.yml`, `feature.md`)
  - Question (`question.yml`, `question.md`)
  - Documentation request (`docs.yml`, `docs.md`)
  - Feedback (`feedback.yml`, `feedback.md`)
  - Task (`task.yml`, `task.md`)
- **Pull Request Template** (`PULL_REQUEST_TEMPLATE.md`)
- **Code Owners** (`CODEOWNERS`)
- **Contribution Guide** (`CONTRIBUTING.md`)
- **Security Policy** (`SECURITY.md`)
- **Support Guidelines** (`SUPPORT.md`)
- **Funding Configuration** (`FUNDING.yml`)

## 🛠️ How to Use

Simply copy the desired templates into the `.github/` directory of your repository.

You can do this manually or using a script. For example:

```bash
curl -o .github/ISSUE_TEMPLATE/bug.yml https://raw.githubusercontent.com/optiflowic/github-templates/main/.github/ISSUE_TEMPLATE/bug.yml
```

All templates are designed to be easily customizable.

## 📝 Customization

- Replace `@your-username` or `@your-org/team` in `CODEOWNERS`
- Replace `[your-email@example.com]` in `SECURITY.md`
- Edit any Markdown template sections to suit your project

## 📎 Notes

- This repository is **tool-agnostic** and does not depend on any CLI or external system.
- Other tools or scripts (e.g. internal generators) may reference this repository.

## 🤝 Contributing

Contributions to improve or expand these templates are welcome!  
Feel free to open an issue or pull request.

## ⚖️ License

This project is licensed under the [MIT License](./LICENSE).
