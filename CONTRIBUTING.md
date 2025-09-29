# Contributing — my-web3-demo

欢迎贡献！本仓库仅用于演示提交/PR 流程与生成可验证贡献记录。任何改动都应保持小体量、低侵入、便于快速 review。

## 快速流程（Fork → Branch → PR）
1. 点击页面右上角的 **Fork** 创建你自己的副本。  
2. 在你的 Fork 上新建分支（推荐格式）：  
3. 在该分支上进行改动（新增文件或修改 README、添加小脚本等）。  
4. 提交时使用清晰的 commit message（见下方规范）。  
5. Push 到你的 Fork，然后在原仓库发起 Pull Request，目标分支为原仓库的 `main`（或 maintainer 指定的分支）。

## Commit Message 规范（建议）
采用简洁的约定，利于维护者快速识别目的：
常见 `type`：
- `feat`: 新功能 / 新文件
- `fix`: 修复问题 / 更正文案
- `docs`: 文档变更
- `chore`: 构建或维护类小改动

示例：

## PR 描述模板（建议粘贴到 PR body）

## 小建议（提高被计入概率）
- 提交到默认分支或在 PR 中清楚标注改动目的更利于快速合并。  
- 尽量保证提交的 commit email 与你的 GitHub 帐号绑定（若使用本地 git，请执行 `git config user.email "you@example.com"` 并确保该邮箱已在 GitHub 上验证）。  
- 不要使用大量自动化“空提交”或垃圾改动；真实、意义明确的小改更稳妥。
