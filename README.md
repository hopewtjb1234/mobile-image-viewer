# 手机图片展示网页

当前 `assets/display-image.jpg` 是你提供的正式图片。

正式网址：<https://hopewtjb1234.github.io/mobile-image-viewer/>

网页会遮住图片左上角原有时间，并显示当前北京时间（每分钟自动更新）。如果更换的图片布局不同，时间遮盖位置可能需要调整。

## 换成你的图片

1. 将正式图片转换或另存为 JPG，文件名改为 `display-image.jpg`。
2. 用它覆盖 `assets/display-image.jpg`。建议单张图片小于 5 MB；通过 GitHub 网页上传的单文件上限为 25 MiB。
3. 在本地打开 `index.html` 检查图片内容和清晰度。
4. 打开 GitHub 仓库 <https://github.com/hopewtjb1234/mobile-image-viewer>，进入 `assets` 文件夹，选择 **Add file → Upload files**，上传同名 `display-image.jpg` 并提交到 `main` 分支。也可以把新图片发给我，由我更新同一仓库。Pages 完成重新部署后，正式网址保持不变。
5. 如果手机还显示旧图，先下拉刷新或重新打开链接；仍未更新时，在网页链接末尾加 `?v=2`（已有 `?` 时改用 `&v=2`）。网页会用同一版本号重新请求图片，以检查缓存。确认更新后仍可分享原网址。

## 本地预览

直接双击 `index.html` 即可预览。也可以使用任意静态文件服务器测试；本地地址不能分享给公网用户。

## 部署提示

本项目没有构建步骤，当前使用 GitHub Pages 免费托管。广州移动、联通、电信、Wi-Fi 和微信内置浏览器的访问效果需要用手机分别实测。
