# st2eam/discover — 摄影原图仓库

仅存放原图，网站代码在 [st2eam.github.io](https://github.com/st2eam/st2eam.github.io)。

## 结构

```
photos/          # 原图（网站通过 jsDelivr 引用）
```

## 工作流

1. 新照片放入本仓库 `photos/`
2. 提交并推送到 `main`
3. 在网站仓库运行 `npm run photos`（需本仓库与网站仓库同级，或设置 `DISCOVER_PHOTOS_DIR`）

原图地址示例：

`https://raw.githubusercontent.com/st2eam/discover/main/photos/DSC00054.jpg`
