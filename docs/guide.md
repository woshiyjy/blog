# 文档编辑指南

## 如何添加新内容

1. 在 `docs` 目录下创建新的 Markdown 文件
2. 使用 Markdown 语法编写内容
3. 在 `mkdocs.yml` 中添加导航配置

### Markdown 语法示例

#### 标题
```markdown
# 一级标题
## 二级标题
### 三级标题
```

#### 列表
```markdown
- 无序列表项
- 另一个列表项

1. 有序列表项
2. 另一个有序列表项
```

#### 代码块
```markdown
```python
print("Hello World")
```
```

#### 链接和图片
```markdown
[链接文字](链接地址)
![图片描述](图片地址)
```

## 如何修改内容

1. 找到需要修改的 `.md` 文件
2. 使用文本编辑器打开文件
3. 修改内容并保存
4. 文档会自动更新

## 本地预览

1. 在项目根目录运行 `mkdocs serve`
2. 访问 `http://127.0.0.1:8000` 预览效果
3. 修改文件时会自动刷新预览

## 部署更新

1. 将修改提交到 Git 仓库
2. 推送到 GitHub 的 main 分支
3. GitHub Actions 会自动构建并部署更新
4. 访问 https://woshiyjy.github.io/mkdocs 查看最新内容