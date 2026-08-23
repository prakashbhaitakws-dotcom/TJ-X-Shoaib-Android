# TJ X Shoaib Mobile Watermark Remover

Android-ready Capacitor project based on the supplied Windows app.

## Features
- Single or batch video selection
- Delogo removal with Dola AI, TikTok/CapCut, Top-right, and custom coordinates
- Bottom-strip crop
- Ultra-Fast / Balanced / High Quality H.264 encoding
- MP4 outputs saved through Android's browser/WebView download flow

## Build APK
1. Install Node.js 20+ and Android Studio with Android SDK.
2. Run `npm install`.
3. Run `npx cap add android`.
4. Run `npx cap sync android`.
5. Open `android/` in Android Studio.
6. Build > Build APK(s).

The FFmpeg WASM engine is loaded from jsDelivr when processing starts. This keeps the project small; internet access is required on first processing unless the FFmpeg WASM assets are bundled locally.
