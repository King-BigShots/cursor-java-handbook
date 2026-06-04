# 建议在 GitHub 上创建的真实 Issue（维护痕迹）

推送仓库后，用你自己的 GitHub 账号创建 **1～2 个** issue，不要由脚本批量伪造。以下为可直接粘贴的标题与正文示例。

---

## Issue 1：文档类

**标题：** `[doc] 希望补充 Maven 标准目录说明`

**正文：**

```markdown
## 出问题的文件

（新章节建议）notes/java/03-Maven-入门.md

## 问题描述

初学者在 Cursor 里打开 Maven 项目时不理解 src/main/java 目录结构，希望手册增加图示或说明。

## 环境

- Windows 11
- JDK 17
```

**标签：** `enhancement`

---

## Issue 2：改进类

**标题：** `[enhancement] 增加 Cursor Agent 模式入门章节`

**正文：**

```markdown
## 建议主题

notes/cursor/03-Agent-模式入门.md

## 为什么有用

读者已会快捷键，下一步需要知道 Agent 与 Chat 的区别，避免误用自动改文件。

## 你是否愿意贡献 PR

- [ ] 暂时只能提建议
```

**标签：** `enhancement`

---

创建 issue 后，在 [MAINTENANCE_LOG.md](./MAINTENANCE_LOG.md) 表格追加一行记录日期与 issue 链接。
