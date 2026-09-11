# Ink UI Kit

一套面向电子纸（e-paper）显示屏的单色 CSS 组件库。纯黑配暖白背景，2px 粗边框作为标志性风格,胶囊形控件,以及一个渲染效果酷似 1-bit 屏幕的面板组件。

## 使用方法

将 `ink-ui-kit.css` 引入你的项目,并在页面(或根元素)上包裹 `.ink-root`:

```html
<link rel="stylesheet" href="ink-ui-kit.css" />
<body class="ink-root">
  <button class="ink-btn ink-btn--primary">Primary</button>
</body>
```

打开 [index.html](index.html) 查看完整的独立参考页面,展示所有颜色、字体样式与组件。

## 包含内容

- **颜色** — 8 级单色色阶,从 `--ink-black` 到 `--ink-white`
- **排版** — 界面使用无衬线字体,引用文字使用衬线字体,数字使用等宽字体
- **间距与圆角** — 以 8px 为基准的间距系统,以及尖角/圆角/胶囊形三种圆角处理
- **组件** — 按钮、胶囊标签(chips)、徽章与标签(badges & tags)、卡片、标志性的电子墨水面板(e-ink panel)、列表、空状态、底部标签栏
- **工具类** — 用于颜色、边框、间距与布局的小型辅助类

所有类名均以 `ink-` 为前缀,不会与现有样式冲突。

## 文件说明

- `ink-ui-kit.css` — 独立样式表
- `index.html` — 离线演示/参考页面
- `artifact.html` — 与参考页面相同的内容,已调整为适合发布为 Claude Artifact 的结构

---

[English](README.md)
