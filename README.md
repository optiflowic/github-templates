# 📦 GitHub Templates

A collection of reusable GitHub repository templates including issue forms, pull request templates, contribution guidelines, and more.

> 🌐 This repository supports **both English (`en/`) and Japanese (`ja/`)** templates.

It aims to provide standardized `.github/` files that can be used across multiple repositories to ensure consistency and reduce setup effort.

## 🧰 Available Templates

Each language has its own directory:

- `en/` for English
- `ja/` for Japanese

### 📝 Issue Templates

- Bug report (`bug.yml`, `bug.md`)
- Feature request (`feature.yml`, `feature.md`)
- Question (`question.yml`, `question.md`)
- Documentation (`docs.yml`, `docs.md`)
- Feedback (`feedback.yml`, `feedback.md`)
- Task (`task.yml`, `task.md`)

### 📥 Pull Request Template

- `PULL_REQUEST_TEMPLATE.md`

### ⚙️ Other Templates

- `CODEOWNERS`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `SUPPORT.md`
- `FUNDING.yml`

## 🛠️ How to Use

Copy the desired templates into your repository’s `.github/` directory.

You can do this manually or via script. Example:

- English version

  ```bash
  curl -o .github/ISSUE_TEMPLATE/bug.yml https://raw.githubusercontent.com/optiflowic/github-templates/main/en/.github/ISSUE_TEMPLATE/bug.yml
  ```

- Japanese version

  ```bash
  curl -o .github/ISSUE_TEMPLATE/bug.yml https://raw.githubusercontent.com/optiflowic/github-templates/main/ja/.github/ISSUE_TEMPLATE/bug.yml
  ```

All templates are designed to be easily customizable.

## 📝 Customization

- Replace `@your-username` or `@your-org/team` in `CODEOWNERS`
- Replace `[your-email@example.com]` in `SECURITY.md`
- Edit any Markdown template sections to suit your project

## 🤝 Contributing

Contributions to improve or expand these templates are welcome!  
Feel free to open an issue or pull request.

## ⚖️ License

This project is licensed under the [MIT License](./LICENSE).
