# 零域方阵

一个可直接部署到 GitHub Pages 的纯前端塔防游戏 Demo。

## 在线部署

这个项目不需要后端服务器。把仓库推到 GitHub 后，在仓库的 Settings -> Pages 里把 Source 设为 GitHub Actions，然后每次推送到 `main` 分支都会自动发布。

发布后的网址通常是：

```text
https://你的用户名.github.io/仓库名/
```

## 本地预览

```bash
python3 -m http.server 5174
```

然后打开：

```text
http://localhost:5174/
```
