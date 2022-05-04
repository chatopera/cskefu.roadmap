# 春松客服路线图

访问文档地址：[https://chatopera.github.io/cskefu.roadmap/](https://chatopera.github.io/cskefu.roadmap/)

# 更新文档

## Add Markdown Files

在 `sources/` 中添加 Markdown 文件，并以 `*.m.md` 作为后缀，该后缀会被 [mark-markdown-up](https://github.com/hailiang-wang/mark-markdown-up) 处理，支持一些 Markdown 的扩展用法。

Start from `sources/index.m.md`, add `xxx.m.md` markdown files described in [mark-markdown-up](https://github.com/hailiang-wang/mark-markdown-up).

## Add Media Assets

在 `assets/` 中添加多媒体文件，比如图片素材等。在 Markdown 文件中，使用 ```![描述](../assets/XXX文件)``` 进行引用。

Add files, artifacts in `assets`.

# 注意事项

* [docs](./docs) 文件夹会在 GitHub 自动更新为 GitHub pages, 以通过 CI 任务自动管理，不要手动管理该文件夹文件
* 最大的节省流量，因为内容主要呈现在一个网页上：图片要不超过 100k，宽度不超过 1000px；图片格式宜使用 jpg

# 构建文档

说明, [MANUAL](./MANUAL.md)

* Build into Office Word

```bash
./scripts/docx.sh
```

* Build into HTML

```bash
./scripts/html.sh
```

To disable the open docs action by default, touch `touch ~/.pandoc_build_not_open`.

# License

[Apache2](./LICENSE)
