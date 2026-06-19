# 🚀 个人简历 - Personal Resume

一个现代化、交互式的个人简历网页，采用深色科技风格设计。

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat&logo=github&logoColor=white)

## ✨ 功能特性

- 🌌 **动态粒子背景** - Canvas 绘制，鼠标交互跟随
- ⌨️ **打字机动画** - 自我介绍逐字展示
- 📅 **时间轴布局** - 教育/工作/项目经历清晰呈现
- 📊 **技能雷达图** - Canvas 八维可视化
- 🧭 **侧边导航栏** - 滚动自动高亮当前板块
- 🌓 **明暗主题切换** - 自动记忆用户偏好
- 📂 **折叠展开交互** - 卡片内容按需查看
- 📄 **导出 PDF** - 一键打印/导出简历
- 📱 **响应式设计** - 完美适配手机/平板/桌面

## 📁 项目结构

```
my-website/
├── index.html          # 简历主页
├── README.md           # 项目说明
├── LICENSE             # 开源协议
├── .gitignore          # Git 忽略配置
└── docs/
    └── compose/
        └── plans/      # 设计文档
```

## 🚀 快速开始

### 本地预览

```bash
# 克隆仓库
git clone https://github.com/yujiansry/my-website.git

# 进入目录
cd my-website

# 打开浏览器预览
open index.html
```

### 部署到 GitHub Pages

1. Fork 或克隆本仓库
2. 修改 `index.html` 中的个人信息
3. 推送到 GitHub
4. 在仓库 Settings → Pages 中启用 GitHub Pages
5. 访问 `https://<你的用户名>.github.io/my-website/`

## 🎨 自定义

### 修改个人信息

编辑 `index.html`，找到以下占位内容并替换：

- `你的名字` → 你的真实姓名
- `138-0000-0000` → 你的手机号
- `your@email.com` → 你的邮箱
- `yourusername` → 你的 GitHub 用户名
- 教育背景、工作经历、技能等板块内容

### 修改主题色

在 `<style>` 标签中修改 CSS 变量：

```css
:root {
  --accent: #6c63ff;        /* 主色调 */
  --accent-light: #8b83ff;  /* 浅色调 */
  --gradient-start: #6c63ff; /* 渐变起始 */
  --gradient-end: #e44dff;   /* 渐变结束 */
}
```

## 📸 功能预览

| 功能 | 说明 |
|------|------|
| 粒子背景 | 鼠标移动时粒子跟随散开 |
| 打字机 | 自我介绍逐字显示 |
| 时间轴 | 教育/工作经历时间线展示 |
| 雷达图 | Canvas 技能可视化 |
| 侧边导航 | 滚动高亮当前板块 |
| 主题切换 | 深色/浅色模式 |

## 🛠️ 技术栈

- **前端**: HTML5 + CSS3 + Vanilla JavaScript
- **图形**: Canvas API (粒子背景 + 雷达图)
- **动画**: CSS Transitions + requestAnimationFrame
- **部署**: GitHub Pages

## 📄 开源协议

本项目采用 [MIT](LICENSE) 协议开源。

## 👨‍💻 作者

**Your Name** - [GitHub](https://github.com/yujiansry)

---

⭐ 如果这个项目对你有帮助，欢迎 Star 支持！
