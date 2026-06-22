# Heyu Space

`heyuspace.com` 的个人入口页。

## 结构

- `index.html`：主页入口
- `404.html`：简单 404 页面
- `_headers`：Cloudflare Pages 安全响应头

## Cloudflare Pages 部署

创建 Pages 项目时选择这个 GitHub 仓库：

- Framework preset: `None`
- Build command: 留空
- Build output directory: `/`

然后绑定自定义域名：

- `heyuspace.com`
- `www.heyuspace.com`

## 子站规划

- `blog.heyuspace.com`：个人博客
- `notes.heyuspace.com`：笔记与折腾记录
- `dash.heyuspace.com`：VPS dashboard
- `status.heyuspace.com`：状态页
- `digvps.heyuspace.com`：低价 VPS 监控
