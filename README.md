# Rosa's Portfolio

张芮绮的个人作品集网页，面向AI产品经理/AI产品运营求职。

## 技术栈

- React 18 + TypeScript
- Vite 5
- Tailwind CSS 3
- Lucide React (图标)

## 项目结构

```
src/
├── components/
│   ├── Navbar.tsx          # 导航栏
│   ├── Hero.tsx            # Hero区域
│   ├── AboutMe.tsx         # 关于我
│   ├── Education.tsx       # 教育背景
│   ├── WorkExperience.tsx  # 工作经历
│   ├── CapabilityModel.tsx # 能力模型
│   ├── PortfolioLinks.tsx  # 作品链接
│   ├── PersonalInterests.tsx # 个人爱好
│   └── Footer.tsx          # 页脚
├── App.tsx
├── main.tsx
└── index.css
```

## 运行项目

```bash
# 安装依赖
npm install

# 开发模式
npm run dev

# 构建
npm run build

# 预览
npm run preview
```

## 部署

项目配置了GitHub Actions自动部署到GitHub Pages。

### 步骤

1. 创建GitHub仓库并推送代码
2. 在仓库设置中开启GitHub Pages
3. 选择 `gh-pages` 分支作为源
4. 每次push到main分支会自动触发部署

## 设计风格

- **配色**: 粉色背景(#FFF0F5) + 绿色主标题(#228B22) + 棕色辅助文字(#8B4513)
- **字体**: Ma Shan Zheng (手写风格标题) + Noto Sans SC (正文)
- **视觉元素**: 手绘线条、星星装饰、卡片式布局

## 页面模块

1. **Hero**: 个人品牌展示
2. **About Me**: 个人介绍、性格特点
3. **教育背景**: 时间线布局展示教育经历
4. **工作经历**: 字节跳动、滴滴、橘宜集团、美图
5. **能力模型**: 产品技能、数据分析、语言能力
6. **作品链接**: 内容运营、市场调研、Vibe Coding项目
7. **个人爱好**: 摄影作品展示