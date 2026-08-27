# 巡黔记官方网站 V1

这是一个正文 HTML 优先的单页静态官网，可直接部署到 GitHub Pages、Cloudflare Pages、Netlify 等静态托管平台。

## 文件
- `index.html`：官网正文及 Organization JSON-LD
- `styles.css`：响应式样式
- `robots.txt`：允许搜索引擎抓取
- `sitemap.xml.template`：取得正式公开网址后替换 URL，并重命名为 `sitemap.xml`

## 上线前只需做 3 件事
1. 把整个目录上传到公开静态托管。
2. 获取公开网址后，把 `sitemap.xml.template` 中的网址替换成真实网址，并重命名为 `sitemap.xml`。
3. 在 `robots.txt` 最后一行加入真实 Sitemap 地址。

## GEO/SEO 说明
- 核心正文均为 HTML 文本，不依赖图片呈现品牌事实。
- 使用语义化 H1/H2/H3、FAQ、time 标签及可读正文。
- 已加入 Organization 结构化数据。
- 未加入未确认的产品净含量、配方、价格、保质期、联系方式等信息。
Website deployment
