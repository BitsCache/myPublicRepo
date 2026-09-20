# 我的公开仓库

这是一个用于图床和GitHub Pages功能的公开仓库。

## 功能

### 图床服务
- 使用 `image_hosting` 文件夹存储图片
- 支持通过GitHub API或直接上传图片
- 提供可直接引用的图片链接

### GitHub Pages
- 使用 `pages` 文件夹存放静态网站文件
- 通过GitHub Pages功能部署网站
- 支持自定义域名（可选）

## 目录结构

```
.
├── image_hosting/    # 图床文件夹，存放图片
├── pages/            # GitHub Pages文件夹，存放静态网站
│   └── index.html    # 网站首页
└── README.md         # 本说明文件
```

## 使用方法

### 图床使用
1. 将图片上传到 `image_hosting` 文件夹
2. 通过以下格式引用图片：
   ```
   https://raw.githubusercontent.com/用户名/仓库名/main/image_hosting/图片文件名
   ```

### GitHub Pages使用
1. 将HTML、CSS、JavaScript等静态文件放入 `pages` 文件夹
2. 在仓库设置中启用GitHub Pages
3. 选择 `main` 分支的 `/pages` 目录作为源
4. 访问 `https://用户名.github.io/仓库名/` 查看网站

## 当前内容

- `pages/index.html` - 一个创意艺术风格的占位页面，展示基本的HTML/CSS动画效果

## 许可证

MIT License