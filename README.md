# my-web3-demo

> 一个小而真实的贡献仓库，用于在 GitHub 上留下可验证的公共贡献痕迹（提高在第三方平台如Legion,plasma等等的可见度）。
> 目标：小体量、低侵入、易审核 —— 任何人都能在 5–20 分钟内完成。

## 原创短介绍
我是个喜欢把想法小步快跑变成代码的人。这个仓库做的很简单：**做一件真实的小事并留下一条可验证的贡献记录**（新增 README / 修正 typo / 加一个小脚本），以证明我在开源社区的参与度。

## 这个仓库包含
- `README.md`：仓库说明（本文件）
- `scripts/hello.py`：一个简单的可运行示例脚本，证明仓库有可执行代码
- `CONTRIBUTING.md`：如何贡献（适用于 Fork → 改 → PR 的场景）

## 为什么做这个仓库
许多按“贡献/社区活跃度”评分的工具或平台会读取 GitHub 的公共贡献信号（创建仓库、commit、PR、issue 等）。本仓库通过极低的门槛产生这些信号，既不破坏任何项目，也能为你的 profile 增添可信的活动痕迹。

## 快速上手（网页操作，零命令行）
1. 登录 GitHub → 点击右上角 `+` → `New repository`。  
2. 仓库名可填 `my-legion-demo`，选择 **Public**。  
3. 创建后点击 `Add file` → `Create new file`，文件名填 `README.md`，把本文件内容粘贴并 `Commit`。  
4. （可选）重复同样方式新建 `scripts/hello.py` 与 `CONTRIBUTING.md`，或在 Fork 后创建新分支并提交到该分支以发 PR。

## 运行示例脚本（如想测试）
```bash
python3 scripts/hello.py
# My-Web3-Demo
Demo repo to create a small, verifiable public contribution for web3 demo
