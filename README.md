# qrcode
qrcode-scanner

# 图书条码扫描器 (ZXing + html5-qrcode fallback)

这是一个可以直接部署到 GitHub Pages 的纯前端网页，支持用手机摄像头快速扫码书籍条码。

## 功能
- 默认使用 [ZXing-js](https://github.com/zxing-js/library)
- 如果 ZXing 初始化失败，会自动切换到 [html5-qrcode](https://github.com/mebjas/html5-qrcode)

## 使用方法
1. 将本项目上传到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 用手机打开 `https://你的用户名.github.io/仓库名/` 即可扫码
