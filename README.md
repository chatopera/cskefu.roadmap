# 春松客服路线图

## Add Markdown Files

在 `sources/` 中添加 Markdown 文件，并以 `*.m.md` 作为后缀，该后缀会被 [mark-markdown-up](https://github.com/hailiang-wang/mark-markdown-up) 处理，支持一些 Markdown 的扩展用法。

Start from `sources/index.m.md`, add `xxx.m.md` markdown files described in [mark-markdown-up](https://github.com/hailiang-wang/mark-markdown-up).

## Add Media Assets

在 `assets/` 中添加多媒体文件，比如图片素材等。在 Markdown 文件中，使用 ```![描述](../assets/XXX文件)``` 进行引用。

Add files, artifacts in `assets`.

## Build

说明, [MANUAL](./MANUAL.md)

* Build into Office Word

```bash
./scripts/build.word.sh
```

* Build into HTML

```bash
./scripts/build.html.sh
```

## License

[Apache2](./LICENSE)
