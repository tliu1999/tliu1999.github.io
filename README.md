# 刘婷个人主页

这是一个纯静态个人主页，可以直接用任意静态服务器托管。

## 本地预览

```bash
python3 -m http.server 8000 --bind 0.0.0.0
```

本机访问：

```text
http://127.0.0.1:8000/
```

同一 Wi-Fi 或局域网内访问：

```text
http://你的局域网IP:8000/
```

## 公开访问

推荐三种方式：

1. GitHub Pages：把 `site` 目录内容提交到仓库，开启 Pages。
2. Netlify / Vercel：直接拖拽或导入 `site` 目录。
3. 临时公网预览：使用 Cloudflare Tunnel、ngrok 等工具把本地 `8000` 端口暴露出去。

公开前建议再次确认是否展示手机号、详细住址等隐私信息。当前页面只展示邮箱、Google Scholar 和 ORCID。
