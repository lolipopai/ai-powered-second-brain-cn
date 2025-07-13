# Obsidian + ChatGPT 个人画像协作工作流

> 利用 Obsidian 构建你的第二大脑，并结合 ChatGPT 实现个性化成长、反思与知识管理。

---

## 🧭 项目目录结构

```
obsidian-chatgpt-profile-loop/
├── README.md                # 项目说明与使用引导
├── personal-vault-template/ # 个人画像模板（markdown 文件）
│   ├── 00-索引.md
│   ├── 01-基本信息.md
│   ├── ...
├── prd.md                   # 产品需求说明文档
├── 画像摘要模板.md          # 提供给 ChatGPT 的个人画像概要结构
├── chatgpt-workflow.md      # 工作流文档 + Mermaid 图
└── LICENSE
```

---

## 📌 项目内容简介

本项目旨在帮助用户：

- 利用 Obsidian 构建结构化的个人画像系统
- 总结画像摘要用于 ChatGPT 协作
- 获取个性化建议（如目标规划、写作反馈、自我反思）
- 构建 Obsidian 与 ChatGPT 协同闭环，持续自我成长

---

## 🌟 与其他项目的差异点

相比现有如 chatgpt-md、obsidian-smart-connections 等插件，本项目更注重：

- 🎯 自我认知导向：结构化的「个人画像」模板（兴趣、性格、技能等）
- 🔁 成长闭环设计：形成 "填写 → 摘要 → GPT 对话 → 反映/记录 → 复盘" 的持续协作流
- 🧠 ChatGPT 协作而非调用：强调的是「你+GPT 的对话式成长」而非工具化插件
- 📦 开箱即用：包含模板 Vault、摘要结构、Mermaid 流程图、PRD 文档等
- 🗂 可复用性高：适合作为他人构建数字身份或长期思维档案的入门示范

---

## ⚙️ 与 Cursor 协作使用指南

本项目包含的 prd.md（产品需求文档）可直接配合 Cursor 使用，实现自动生成 Obsidian 文件结构、模板和脚手架：

1. 打开 Cursor，新建空白项目或 Markdown 工程
2. 将 prd.md 复制粘贴进项目中，并选中让 GPT 运行任务（"Implement this" 或 "Generate structure"）
3. Cursor 将自动创建 personal-vault-template 文件夹及所有 Markdown 模板页面
4. 后续你可在 Cursor 中继续迭代内容，并同步到你的本地 Obsidian Vault

📌 建议在 prd.md 中使用中文书写明确模块名、字段结构、内容指引，GPT 在 Cursor 中表现良好

---

## 🛠️ 使用方法

1. 克隆本项目或下载 zip
2. 将 personal-vault-template/ 导入 Obsidian 作为新 Vault
3. 根据模板填写你的个人画像内容
4. 在 画像摘要模板.md 中维护你的核心画像概要
5. 将概要复制粘贴到 ChatGPT 中（建议设置到 Custom Instructions）
6. 与 ChatGPT 进行深度对话，并将输出记录回 Vault
7. 定期复盘更新画像，形成成长闭环

---

## 🧠 工作流示意图（Mermaid）

```mermaid
flowchart TD
    A[建立 Obsidian 个人画像] --> B[填写各主题页面]
    B --> C[生成个人画像摘要]
    C --> D[将摘要粘贴给 ChatGPT\n(或写入 Custom Instructions)]
    D --> E[获得个性化建议/反思/协作]
    E --> F[将重要内容记录回 Obsidian\n（如日记、目标更新）]
    F --> G[定期回顾与更新画像摘要]
    G --> C
```

---

## 🔖 推荐插件（可选）

- Templater：自动插入个人画像结构
- Dataview：生成摘要或动态引用内容
- Periodic Notes：定期复盘
- Excalidraw：图像化反思

---

## 📃 许可协议

MIT License © 2025 Zhang Cheng

---

如你喜欢本项目，欢迎 ⭐Star 并分享给你的朋友！也欢迎 PR 提交新的画像模块、工作流建议或英文版翻译 🙌
