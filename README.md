# 个人博客项目

这是我的个人博客项目，基于MkDocs Material主题构建的静态网站，用于展示个人简介、项目经历和教育背景等内容。

## 技术栈

- MkDocs：静态网站生成器
- Material for MkDocs：现代化主题
- GitHub Pages：网站托管
- GitHub Actions：自动化部署

## 特性

- 响应式设计，支持移动端访问
- 深色/浅色主题切换
- 代码高亮和复制功能
- 全文搜索
- 数学公式支持
- 图片懒加载和缩放

## 本地开发

1. 克隆项目
```bash
git clone https://github.com/woshiyjy/blog.git
cd blog
```

2. 安装依赖
```bash
pip install mkdocs-material
```

3. 本地预览
```bash
mkdocs serve
```

访问 http://127.0.0.1:8000 查看效果

## 部署

项目通过GitHub Actions自动部署到GitHub Pages。每次推送到main分支时会自动触发部署流程。

在线访问地址：https://woshiyjy.github.io/blog

## 目录结构

```
├── docs/               # 文档目录
│   ├── index.md       # 首页（自我介绍）
│   ├── project.md     # 项目经历
│   └── educate.md     # 教育经历
├── mkdocs.yml         # MkDocs配置文件
└── .github/workflows/ # GitHub Actions配置
```

## 许可证

本项目采用MIT许可证。详见 [LICENSE](LICENSE) 文件。
