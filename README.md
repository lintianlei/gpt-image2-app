# GPT IMAGE2

AI 图像生成 App — 基于 Capacitor + PWA

## 功能
- 🎨 AI 图像生成（提示词输入 + 15 种比例 + 尺寸/质量/格式）
- 📱 5 页面 Tab 导航：首页 / 作品库 / 提示词收藏 / API 设置 / 我的
- 📤 图片上传编辑
- ⚙️ 自定义 API（gpt-image-2 / gpt-image-2-vip / gpt-image-2-all）
- 💾 生成结果预览与保存
- 🌐 提示词灵感广场（opennana.com）

## 运行
```bash
npm install
npx serve .
```

## 构建 APK
```bash
npm install
npx cap add android
npx cap sync android
cd android && ./gradlew assembleDebug
```

APK 输出路径: `android/app/build/outputs/apk/debug/app-debug.apk`

## GitHub Actions 自动构建
推送代码到 main 分支后，GitHub Actions 会自动构建 APK 并发布到 Releases。
