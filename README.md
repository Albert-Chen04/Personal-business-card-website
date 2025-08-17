# Albert's Personal Homepage

![Website Screenshot](assets/images/screenshot.png) <!-- 建议您截一张网站的图，并命名为 screenshot.png 放在 assets/images/ 目录下 -->

欢迎来到我的个人主页项目仓库。这是一个从零开始构建的、现代化的、响应式的静态网站，用于展示我的个人信息、项目、技能和社交链接。

**[➡️ 访问在线演示](https://Albert-Chen04.github.io)** <!-- 请将此链接替换为您部署后的真实网址 -->

---

## ✨ 主要特色

- **完全响应式设计**: 无论在桌面、平板还是手机上，都能提供优美的浏览体验。
- **清晰的模块化结构**: 项目遵循内容(HTML)、表现(CSS)、行为(JavaScript)三者分离的原则，代码结构清晰，易于维护和扩展。
- **组件化CSS**: 使用独立的CSS文件管理页面各个部分的样式，修改特定区域的样式变得非常简单。
- **原生JS交互**: 所有交互功能（如导航、弹窗、筛选）均使用原生JavaScript实现，轻量且无依赖。
- **现代化UI/UX**: 简洁的设计、平滑的动画效果和优秀的用户体验。
- **易于定制**: 只需修改HTML文件和`assets/css/main.css`中的CSS变量，即可轻松定制个人信息和主题颜色。

---

## 🛠️ 技术栈

- **HTML5**: 采用语义化标签，结构清晰，对SEO友好。
- **CSS3**:
  - 使用 **Flexbox** 和 **Grid**进行布局。
  - 使用 **CSS自定义属性 (变量)** 管理主题颜色和尺寸，方便一键换肤。
- **Vanilla JavaScript (ES6+)**: 无任何框架依赖，实现所有动态交互。
- **Font Awesome**: 用于展示丰富的图标。
- **Google Fonts**: 提供高质量的网页字体。

---

## 📁 项目结构

项目采用结构化的目录，将不同类型的文件分类存放。

```
/Albert-Homepage/
|
├── index.html              # 网站主入口
|
├── assets/                 # 静态资源
|   |
|   ├── css/                # 样式
|   |   ├── main.css        # 主样式与全局变量
|   |   └── components/     # 组件样式
|   |       ├── _header.css
|   |       └── ... (其他组件)
|   |
|   ├── js/                 # 脚本
|   |   └── main.js         # 所有交互逻辑
|   |
|   └── images/             # 图片
|       ├── avatar.jpg
|       └── ... (其他图片)
|
└── README.md               # 项目说明
```

---

## 🚀 如何开始

您可以轻松地克隆本项目，并进行个性化修改。

### 1. 克隆仓库

```bash
git clone https://github.com/Albert-Chen04/Albert-Homepage.git
```

### 2. 进入项目目录

```bash
cd Albert-Homepage
```

### 3. 在浏览器中打开

直接在浏览器中打开 `index.html` 文件即可预览网站。

为了获得更好的开发体验（例如实时刷新），推荐使用 VS Code 的 **Live Server** 插件来运行项目。

---

## 🎨 如何定制

您可以非常方便地将这个网站修改为您自己的个人主页。

1.  **修改个人信息**:
    - 打开 `index.html` 文件。
    - 替换所有文本内容，例如“关于我”的介绍、项目描述、时间线事件等。
    - 替换所有的链接，例如您的GitHub、B站、微博链接。

2.  **替换图片**:
    - 将您的个人头像命名为 `avatar.jpg` 并替换 `assets/images/` 目录下的同名文件。
    - 同样地，替换 `favicon.ico`、项目封面图和二维码图片。
    - **注意**: 如果您使用了不同的文件名，请务必在 `index.html` 的 `<img>` 标签中更新 `src` 路径。

3.  **修改颜色主题**:
    - 打开 `assets/css/main.css` 文件。
    - 在顶部的 `:root` 选择器中，修改CSS变量的值即可改变整个网站的主题色。
    ```css
    :root {
        --primary-color: #6a5af9; /* 主要颜色 */
        --highlight-color: #ff7e5f; /* 高亮/渐变色 */
        /* ... 其他颜色 */
    }
    ```

4.  **添加/修改项目**:
    - 在 `index.html` 的 `<section id="projects">` 中，复制一个 `project-card` 块并修改其中的内容即可添加新项目。

---

## 📜 许可证

本项目采用 [MIT License](LICENSE)。 <!-- 如果您想添加许可证，可以创建一个名为 LICENSE 的文件 -->