# 苦恼索引急救站

一个零依赖静态网站。打开 `index.html` 就能本地预览，也可以直接部署到 GitHub Pages、Netlify、Vercel、Cloudflare Pages 或任何静态网站托管服务。

## 本地预览

直接双击 `index.html` 可以使用。也可以在本目录启动静态服务器：

```powershell
python -m http.server 8080
```

然后访问：

```text
http://localhost:8080
```

## 部署方式

把当前目录作为静态站点根目录上传到托管平台即可。

- GitHub Pages：提交到仓库后，在 Pages 设置中选择该目录或把 `index.html` 放到发布分支根目录。
- Netlify / Cloudflare Pages：拖拽整个文件夹上传即可。
- Vercel：导入仓库，Framework Preset 选择 `Other`，输出目录保持当前目录。

## 文件结构

```text
index.html   # 网站页面、样式和交互逻辑
README.md    # 运行和部署说明
```
