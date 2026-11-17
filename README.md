# Interstellar · 公开演示

12 页静态网页，保留课堂演示的英文叙事、版式、动效与演讲者模式。第 3 页通过片方的页面访问预告片。图片来源与许可见 [Credits & source](docs/credits.html)。

## 本地打开

在项目根目录的 PowerShell 运行：

```powershell
python -m http.server 4173 --bind 127.0.0.1 --directory docs
```

用浏览器打开 http://127.0.0.1:4173/ 。左右键翻页，Esc 打开总览，B 切换静态模式，P 打开演讲者模式及观众窗口。

## 更新和发布

- 直接维护 `docs/index.html` 内的 HTML、CSS 和 JavaScript。原始可编辑插图在 `docs/media/`，新增素材时保留许可和署名。
- 页面和资源使用相对路径。GitHub Pages 的发布源选择 `main` 和 `/docs`。启用后，推送到 `main` 会自动更新网站。
- 代码改编自 Guizang PPT Skill，适用代码采用 AGPL-3.0。内嵌字体采用 SIL OFL 1.1。第三方科学照片按各自的来源及条款使用，详见署名页面。
