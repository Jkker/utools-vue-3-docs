<div align="center">
  <a href="https://github.com/Jkker/utools-ant-design-docs">
    <img src="https://github.com/Jkker/utools-ant-design-docs/raw/main/src/ant-design.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">uTools Ant Design Documentation</h3>
  <p align="center">
    一键查询 Ant Design 文档
    <br />
    <br />
    <a href="https://github.com/Jkker/utools-ant-design-docs/issues">Report Bug</a>
    ·
    <a href="https://github.com/Jkker/utools-ant-design-docs/issues">Request Feature</a>
  </p>
</div>

## 功能预览
![Preview](https://raw.githubusercontent.com/Jkker/utools-ant-design-docs/main/docs/utools-ant-design-docs.webp)


## 选项设置

通过 `Ant Design Setting` 指令打开设置页面，可以设置以下选项：

![Setting](https://raw.githubusercontent.com/Jkker/utools-ant-design-docs/main/docs/utools-ant-design-docs-settings.webp)

- 文档语言: 中文 / 英文
- 镜像地址：[国内官方镜像](https://ant-design.antgroup.com/) / [Global Site](https://ant.design)
- 打开方式: 使用系统默认浏览器打开 / 使用 uTools 内置浏览器打开


## 实现原理

通过调用 Ant Design 的官方 algolia API 查询文档

```json
{
  "x-algolia-application-id": "BH4D9OD16A",
  "x-algolia-api-key": "60ac2c1a7d26ab713757e4a081e133d0",
  "url": "https://bh4d9od16a-dsn.algolia.net/1/indexes/*/queries"
}
```

