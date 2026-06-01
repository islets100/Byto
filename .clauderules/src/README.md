# Claude 学习包（pico）

本目录提供一套用于“从0到1拆解 pico 项目”的提示词与 skills。
适合在 Claude Code 中作为项目级学习指令，也可迁移到 pico 的 skills 目录。

## 文件说明
- claude_code_prompt.md：主提示词
- skills/：3 个可复用 skill
  - pico-map：架构地图与阅读顺序
  - pico-rebuild：最小复现路线
  - pico-deepdive：模块深挖

## 用法建议
1) 将 claude_code_prompt.md 内容合并到你常用的 Claude Code 指令文件中
   - 如果仓库已有 CLAUDE.md，请手动合并，避免覆盖已有约束
2) 如果希望在 pico 内直接使用这些 skills：
   - 将 skills/ 目录复制到项目根目录的 skills/ 或 .pico/skills/
   - pico 只会从这两个位置加载项目 skills
