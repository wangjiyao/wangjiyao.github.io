# wangjiyao.github.io

简约的个人展示页，基于 Jekyll 和 GitHub Pages 构建。

## 维护首页内容

首页内容集中在 `_data/profile.yml`：

- `name`、`role`、`tagline`：首屏文案
- `location`、`availability`：状态信息
- `links`：链接卡片（GitHub、Email 等）

修改数据后无需改动 HTML。模板在 `index.html`。

## 本地预览

```console
bundle install
bundle exec jekyll serve
```

打开 `http://127.0.0.1:4000` 查看效果。

## 部署

推送到 `main` 或 `master` 后，`.github/workflows/pages-deploy.yml` 会自动构建并部署到 GitHub Pages。
