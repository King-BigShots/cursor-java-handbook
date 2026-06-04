# 将本仓库发布到 GitHub

## 第一步：在 GitHub 创建空仓库

1. 登录 GitHub，点击右上角 **+** → **New repository**
2. Repository name 建议：`cursor-java-handbook-zh`
3. 选择 **Public**
4. **不要**勾选 “Add a README file”（本地已有内容）
5. 点击 **Create repository**

## 第二步：本地关联并推送

在 PowerShell 中进入本项目目录：

```powershell
cd "c:\JavaDev\codex-活动"
```

若尚未初始化 Git（本项目已含 `.git` 时可跳过 `git init`）：

```powershell
git init
git branch -M main
```

添加远程仓库（把 `YOUR_USERNAME` 换成你的 GitHub 用户名）：

```powershell
git remote add origin https://github.com/YOUR_USERNAME/cursor-java-handbook-zh.git
git push -u origin main
```

若远程已存在，使用：

```powershell
git remote set-url origin https://github.com/YOUR_USERNAME/cursor-java-handbook-zh.git
git push -u origin main
```

## 第三步：验证

- 浏览器打开：`https://github.com/YOUR_USERNAME/cursor-java-handbook-zh`
- 确认 README、LICENSE、notes 目录均可见
- 确认 **Settings → General → Visibility** 为 Public

## 常见问题

**推送需要登录：** 使用 GitHub Personal Access Token 作为密码，或配置 SSH key。

**仓库名不一致：** 申请表里的 URL 必须与实际仓库名完全一致。
