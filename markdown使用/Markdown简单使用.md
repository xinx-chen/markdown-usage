# Markdown简单使用

## 图片

**相对路径**：如果图片和 Markdown 文件在同一个项目目录下，建议使用相对路径。这种方式在 GitHub 和本地预览时都能正常显示。

```markdown
![图片描述](相对路径./images/your_image.png)
```

这里的 `./images/your_image.png` 假设你的图片位于项目目录下的 `images` 文件夹中。

**绝对路径**：如果你的图片已经在电脑的某个位置，也可以使用该图片在 GitHub 的项目上的 URL。

```markdown
![图片描述](绝对路径）
```