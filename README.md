# neat-freak

Knowledge and Governance Closeout skill（洁癖收尾）。

让代码、真实运行态、项目文档、Agent 规则、获准维护的记忆和工作区状态彼此一致，让下一次会话或第一次接手的人能找到唯一现役答案。

## 触发场景

- 用户说「neat-freak」「洁癖」「/neat」
- 收尾意图：把文档和记忆整理一下、docs 和代码对不上了、交接前同步
- 审计工作区规则是否真的被遵守

## 安装

把整个目录（`SKILL.md` + `evals/` + `references/` + `scripts/`）放到你的 Agent skill 目录，如 `~/.agents/skills/neat-freak/`。

## 内容

- `SKILL.md` — 核心收尾流程（轻量五步 / 完整七步）
- `references/` — 平台路径、治理规则、同步矩阵、验证标准
- `scripts/audit-inventory.sh` — 只读盘点脚本（需 Bash）
- `evals/` — 11 个场景的收尾质量评测

## 版本

v3.0.0 · category: knowledge-governance · 兼容任何 Agent Skills 平台
