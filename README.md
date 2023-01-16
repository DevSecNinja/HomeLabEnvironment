# Home Lab Environment

This repository contains the documentation and code that I use to deploy my Home
Lab environment with Terraform, Ansible, Kubernetes and Helm.

> ⚠️ Note that this repository is under development and some of the
functionalities mentioned might not have been released yet.

## 📌 Features

- Creates Kubernetes VMs on my ESXi host by using Ansible
- Uses Terraform to deploy my applications packaged with Helm

## 🔧 Usage

One of my goals is to make the code as modular as possible so that users can
easily adopt pieces of my code without having to implement all of the technologies
that I'm using.

Documentation is written with Obsidian #REF008-obsidian which allows me to use features
like tags to link non-functional requirements to architecture decisions.

## 📄 Architecture

Inspired by #REF003-nygard  and #REF001-home-assistant, I document requirements
and design decisions in the `/docs/architecture` folder in separate files.

<!-- TODO: Add architecture diagram and context -->

## 🤝 Contributions

I welcome contributions to this project! If you have an idea for a feature or
improvement, please open an issue or pull request. If you find this project
helpful, I would also appreciate it if you could leave a star on the GitHub
repository! 🌟

Thank you for considering contributing 🙏

## 📜 License

This project is licensed under the MIT License. It is not affiliated with my employer.

Feel free to use and modify the code as you see fit 🎉

## 📚 References

Thank you to the following creators for their inspiration. Their work has been
invaluable in shaping the design and development of this project.

| Reference | Description | Author | Note |
|  -------- | ----------- | ------ | ---- |
| #REF001-home-assistant | [Home Assistant](https://github.com/home-assistant) |  Home Assistant Community  | Both the Home Assistant project, but especially their approach to documenting design decisions |
| #REF002-techno-tim | [Techno Tim - YouTube](https://www.youtube.com/c/technotimlive) | Techno Tim | Tim's content on YouTube helped me tremendously setting up my home lab |
| #REF003-nygard | [Documenting Architecture Decisions (cognitect.com)](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions) | Michael Nygard | Describes how to document design designing for Agile projects |
| #REF004-mooney | [GitHub - alstr/todo-to-issue-action](https://github.com/alstr/todo-to-issue-action) | Alastair Mooney | Converts `TODO` comments to GitHub issues automatically by GitHub Actions
| #REF005-gh-linter | [GitHub - github/super-linter](https://github.com/github/super-linter) | GitHub Community | GitHub Action that for linting my code and docs |
| #REF006-tfdocs | [terraform-docs](https://terraform-docs.io/) | terraform-docs Authors | Automatically generates documentation for my GitHub code |
| #REF007-chatgpt | [ChatGPT (openai.com)](https://chat.openai.com/chat) | OpenAI | ChatGPT saves a lot of time by writing documentation or code snippets |
| #REF008-obsidian | [Obsidian](https://obsidian.md/) | Obsidian | Useful program to write documentation in Markdown |
