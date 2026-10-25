> [!NOTE]
> **This skill now lives in the main collection: [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills/tree/main/skills/dockerize-anything)**. Please ⭐ star it there; that's where updates land first.
> Docs: **https://milad-ahmd.github.io/agent-skills/skills/dockerize-anything/** · Claude Code: `/plugin install all-skills --marketplace milad-ahmd/agent-skills`

<div align="center">

# 🐳 dockerize-anything

**Production-ready, small, secure Dockerfile and compose for any repo. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/dockerize-anything)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/dockerize-anything?style=social)](https://github.com/milad-ahmd/dockerize-anything)
![Category](https://img.shields.io/badge/category-DevOps-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/dockerize-anything/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- dockerize-anything
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/dockerize-anything /tmp/dockerize-anything
mkdir -p ~/.claude/skills && cp -r /tmp/dockerize-anything/skills/dockerize-anything ~/.claude/skills/
```

**Per project:** copy `skills/dockerize-anything` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/dockerize-anything/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Dockerize this project
Make my Docker image smaller
```

The full workflow, rules and output format are in [`SKILL.md`](skills/dockerize-anything/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
