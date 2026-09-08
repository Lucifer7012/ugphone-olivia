# Ugphone Olivia

Ugphone Olivia 是一个简洁的个人联系方式页面，使用纯 HTML 和 CSS 制作，并通过 GitHub Pages 免费托管。

## 在线地址

- 网站：https://lucifer7012.github.io/ugphone-olivia/
- GitHub 仓库：https://github.com/Lucifer7012/ugphone-olivia

## 当前页面内容

- 页面名称：Ugphone Olivia
- 身份介绍：UgPhone Official Owner | Reseller Manager
- 说明文字：Join our community for help or partnership!
- Discord：https://discord.gg/ugphone-official
- X/Twitter：暂未添加

## 文件结构

```text
.
├── index.html       # 页面内容和联系方式
├── style.css        # 页面样式、背景模糊和响应式布局
├── background.png   # 全屏背景图片
├── olivia.png       # 圆形头像图片
└── README.md        # 项目说明文档
```

## 修改页面

### 修改文字

打开 `index.html`，可以修改以下内容：

```html
<title>Ugphone Olivia</title>
<h1>Ugphone Olivia</h1>
<p>UgPhone Official Owner | Reseller Manager</p>
<p>Join our community for help or partnership!</p>
```

### 修改 Discord 链接

在 `index.html` 中找到 Discord 按钮，将 `href` 后面的地址替换为新的邀请链接：

```html
<a href="https://discord.gg/你的邀请链接">
```

### 添加其他联系方式

可以复制 Discord 按钮的结构，修改按钮文字和链接。例如邮箱链接：

```html
<a class="contact-button discord-button" href="mailto:example@example.com">
  Email
</a>
```

### 更换图片

直接用同名文件替换仓库根目录中的图片即可：

- `background.png`：背景图片
- `olivia.png`：头像图片

如果修改了文件名，也要同步修改 `index.html` 和 `style.css` 中的图片路径。

## GitHub Pages 设置

本项目使用 `main` 分支的根目录发布。设置位置：

`Settings` → `Pages` → `Build and deployment` → `Deploy from a branch`

选择：

- Branch：`main`
- Folder：`/ (root)`

保存后，GitHub 会自动构建并更新网站。通常需要等待几十秒到几分钟。

## 设计说明

页面保留了原联系方式链接的视觉效果：

- 全屏游戏主题背景
- 背景轻微模糊和暗色遮罩
- 中央蓝紫渐变卡片
- 圆形头像和发光边框
- 居中的 Discord 联系按钮
- 适配手机、平板和电脑屏幕
