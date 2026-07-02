# wangjiyao.github.io

个人主页，基于 Jekyll 和 GitHub Pages 构建。

## 维护首页内容

首页内容集中在 `_data/profile.yml`：

- `name`、`role`、`headline`、`intro`：首页首屏文案
- `links`：首屏按钮链接
- `focus`：个人关注方向标签
- `stats`：右侧数据展示
- `projects`：作品卡片
- `timeline`：Now / Next 模块

修改数据后不需要改 HTML 结构。首页模板在 `index.html`。

## 本地预览

```console
bundle install
bundle exec jekyll serve
```

打开 `http://127.0.0.1:4000` 查看效果。

## 构建检查

```console
bundle exec jekyll build
```

## 部署

推送到 `main` 或 `master` 后，`.github/workflows/pages-deploy.yml` 会自动构建并部署到 GitHub Pages。
