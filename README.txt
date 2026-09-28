CodePad PWA
===========

用途
----
一个非常轻量的 iPhone 代码编辑器。
不运行代码，只用于：
- 粘贴和编辑 Python / TXT
- 保留代码缩进
- Python 自动缩进
- 导入 .py / .txt
- 导出 .py / .txt
- 本地保存
- 离线使用
- 添加到 iPhone 主屏幕

部署
----
PWA 必须通过 HTTPS 网站访问，不能直接在“文件”App里打开 index.html 后安装。

最简单的部署方法：
1. 将本文件夹全部上传到 GitHub 仓库。
2. 开启 GitHub Pages。
3. 使用 iPhone Safari 打开 Pages 地址。
4. Safari -> 分享 -> 添加到主屏幕。
5. 第一次在线打开后，即可离线使用。

也可以部署到：
- Cloudflare Pages
- Netlify
- Vercel
- 任意 HTTPS 静态网站

文件
----
index.html
manifest.webmanifest
sw.js
icon-180.png
icon-192.png
icon-512.png
README.txt
