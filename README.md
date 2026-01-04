# 📚 学术分享海报生成器

一款专为科研工作者设计的知识分享海报生成工具，支持 Markdown 语法，一键生成适配小红书等社交平台的精美竖版海报。

> 🎨 **在线体验**：[https://mingfenghong.github.io/xhs-poster-generator/](https://mingfenghong.github.io/xhs-poster-generator/)  
> 📱 **作者小红书**：[@汤圆键盘坏了不能写论文](https://xhslink.com/m/8hVv9FFnXQj) - 计算社会科学笔记分享

---

## ✨ 核心特性

| 特性 | 说明 |
|------|------|
| 🎯 **多种比例** | 支持 4:5、3:4、9:16 三种竖版比例，适配不同平台 |
| 🎨 **9种主题** | 6种预设栏目 + 3种自定义栏目，马卡龙配色方案 |
| 📝 **Markdown** | 支持粗体、斜体、列表、引用、代码块、数学公式 |
| 🖼️ **图片支持** | 本地上传或URL引用，自动压缩优化 |
| 📄 **多格式导出** | ZIP（PNG图片集）/ PDF 两种导出方式 |
| ⚡ **实时预览** | 所见即所得，分页导航浏览 |
| 📱 **响应式** | 桌面端左右布局，移动端自动适配 |

---

## 🚀 快速开始

### 本地使用
```bash
# 直接用浏览器打开
open index.html
```

### GitHub Pages 部署
1. Fork 或上传本项目到你的 GitHub 仓库
2. 进入 **Settings → Pages**
3. Source 选择 **main** 分支，点击 Save
4. 访问 `https://你的用户名.github.io/仓库名/`

---

## 📖 使用指南

### 1️⃣ 选择栏目
在「封面」选项卡选择分享类型：
- 📄 论文分享（玫瑰粉）
- 💡 理论分享（青绿色）
- 🔧 方法学习（深蓝色）
- ⚙️ 工具分享（紫色）
- ✍️ 思考随笔（琥珀橙）
- 📚 阅读笔记（红橙色）
- 🎨 自定义栏目 ×3

### 2️⃣ 填写内容
- **主标题**：学习主题（支持调整字号）
- **副标题**：可选，显示在主标题下方
- **摘要**：封面页简介
- **封面插图**：上传图片或输入URL

### 3️⃣ 编写正文
在「正文」选项卡使用 Markdown 语法：


**分页规则**：每个 `###` 小标题自动创建新页面

### 4️⃣ 导出海报
在「导出」选项卡选择：
- **ZIP 包**：每页单独保存为 PNG（适合社交媒体）
- **PDF 文件**：合并为单个文档（适合分享打印）

---

## 🛠️ 技术栈

- **前端**：HTML5 + CSS3 + JavaScript (ES6+)
- **Markdown**：[Marked.js](https://marked.js.org/)
- **数学公式**：[KaTeX](https://katex.org/)
- **代码高亮**：[Highlight.js](https://highlightjs.org/)
- **图片导出**：[html2canvas](https://html2canvas.hertzen.com/)
- **文件打包**：[JSZip](https://stuk.github.io/jszip/) + [jsPDF](https://github.com/parallax/jsPDF)

---

## 📁 项目结构

```
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── app.js          # 应用逻辑
├── assets/             # 默认图片资源
├── lib/                # 本地依赖库（可选）
└── README.md
```

---

## 📝 注意事项

1. **浏览器**：推荐使用 Chrome、Edge 或 Firefox
2. **网络**：首次使用需联网加载 CDN 依赖
3. **图片**：推荐上传本地图片，远程URL可能因跨域限制导出失败
4. **分页**：每个 `###` 标题创建新页，注意控制页数

---

## 📄 许可证

MIT License - 欢迎自由使用和修改

---

## 💬 联系作者

- **小红书**：[@汤圆键盘坏了不能写论文](https://xhslink.com/m/8hVv9FFnXQj)
- 📒 计算社会科学笔记 | 管科专业在读
- 📊 网络分析 | NLP | 仿真 | 质性 | 因果推断
- ✉️ 欢迎交流讨论，不接辅导～

---

<p align="center">
  <i>🎓 AI时代，文科有用丨祝你科研顺利～</i>
</p>
