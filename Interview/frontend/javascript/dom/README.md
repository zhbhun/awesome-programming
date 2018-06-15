- [Page lifecycle: DOMContentLoaded, load, beforeunload, unload](https://javascript.info/onload-ondomcontentloaded)

---

## 属性

### attribute VS property

> “Attribute” 是在 HTML 中定义的，而 “property” 是在 DOM 上定义的。

## 事件

### 加载

- document.DOMContentLoaded：当初始的 HTML 文档被完全加载和解析完成之后，DOMContentLoaded事件被触发，而无需等待样式表、图像和子框架的完成加载。
- document.load：在 DOM 和所有相关资源全部完成加载后才会触发。
