# LangGPT Skill

这个仓库用于分发官方原始 `langgpt.skill` 安装包，方便直接下载和安装。

This repository distributes the original `langgpt.skill` package from the official LangGPT project for convenient installation.

Upstream / 上游项目:
- https://github.com/langgptai/LangGPT

## Included / 包含内容

- `langgpt.skill`: 官方原始 skill 打包文件

本仓库**不修改** `langgpt.skill` 的内容。

This repository does **not** modify the package contents.

## Install For Claude Code / 安装到 Claude Code

1. Clone 本仓库，或者直接下载 `langgpt.skill`
2. 创建 Claude Code 的技能目录：

```bash
mkdir -p ~/.claude/skills
```

3. 将安装包解压到该目录：

```bash
unzip langgpt.skill -d ~/.claude/skills
```

4. 重启 Claude Code
5. 在 Claude Code 中使用 LangGPT，例如输入 `/langgpt`，或者直接让它“使用 LangGPT 编写/优化提示词”

## Install For Codex / 安装到 Codex

如果你想把这个包安装到 Codex 风格的本地技能目录中：

1. Clone 本仓库，或者直接下载 `langgpt.skill`
2. 创建 Codex 的技能目录：

```bash
mkdir -p ~/.codex/skills
```

3. 将安装包解压到该目录：

```bash
unzip langgpt.skill -d ~/.codex/skills
```

4. 重启 Codex，让它重新发现新技能
5. 在提问中明确要求使用 `LangGPT` 来编写或优化提示词

## Verify Installation / 验证安装

解压后，你应该看到类似目录结构：

```text
~/.claude/skills/langgpt/
  SKILL.md
  references/
```

or:

```text
~/.codex/skills/langgpt/
  SKILL.md
  references/
```

## Typical Use Cases / 常见用途

- 编写新的结构化 system prompt
- 把普通 prompt 改造成角色化 prompt
- 优化已有 GPT / Claude / 其他 LLM 提示词
- 设计可复用的 AI 角色、工作流和提示词模板

## License And Attribution / 许可与归属

项目许可和更多说明请参考上游仓库：
- https://github.com/langgptai/LangGPT
