<div align="center">
  <a href="https://github.com/Jkker/utools-vue-3-docs">
    <img src="https://github.com/Jkker/utools-vue-3-docs/raw/main/src/vue-3.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">uTools Vue 3 Documentation</h3>
  <p align="center">
    一键查询 Vue 3 文档
    <br />
    <br />
    <a href="https://github.com/Jkker/utools-vue-3-docs/issues">Report Bug</a>
    ·
    <a href="https://github.com/Jkker/utools-vue-3-docs/issues">Request Feature</a>
  </p>
</div>

## 功能预览
![Preview](https://raw.githubusercontent.com/Jkker/utools-vue-3-docs/main/docs/utools-vue-3-docs.webp)


## 选项设置

通过 `Vue 3 Setting` 指令打开设置页面，可以设置以下选项：

![Setting](https://raw.githubusercontent.com/Jkker/utools-vue-3-docs/main/docs/utools-vue-3-docs-settings.webp)

- 文档语言: 中文 / 英文
- 打开方式: 使用系统默认浏览器打开 / 使用 uTools 内置浏览器打开


## 实现原理

通过调用 Vue 3 的官方 algolia API 查询文档

```json
{
  "x-algolia-application-id": "UURH1MHAF7",
  "x-algolia-api-key": "c23eb8e7895f42daeaf2bf6f63eb4bf6",
  "url": "https://uurh1mhaf7-dsn.algolia.net/1/indexes/*/queries"
}
```

