# 我的技术文档

这是我的 GitHub Pages 自动部署实践项目。我用 MkDocs Material 构建文档网站，并通过 GitHub Actions 在推送后自动发布。

- [访问公开网站](https://nexus610.github.io/my-docs/)
- [查看个人实验报告](report/README.md)

## 本地预览

在 Windows PowerShell 中进入仓库根目录，使用 Python 3.12 逐行运行：

```powershell
py -3.12 -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m mkdocs serve
```

在浏览器打开终端显示的预览地址。
