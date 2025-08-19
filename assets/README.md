# 📁 资源文件说明

本目录包含TOMO应用相关的所有静态资源文件，包括图标、截图、演示视频等。

## 📂 目录结构

```
assets/
├── README.md                 # 本说明文件
├── logo.png                  # 应用主Logo (120x120)
├── icon.ico                  # 应用图标文件
├── screenshots/              # 应用截图目录
│   ├── home-screen.png       # 主界面截图
│   ├── search-results.png    # 搜索结果页面
│   ├── voice-input.png       # 语音输入界面
│   ├── voice-recognition.png # 语音识别结果
│   ├── camera-interface.png  # 拍照界面
│   ├── ocr-results.png       # OCR识别结果
│   ├── floating-ball.png     # 悬浮球展示
│   ├── ota-integration.png    # OTA集成效果
│   ├── price-trend.png       # 价格趋势图
│   ├── detailed-comparison.png # 详细比价结果
│   ├── settings.png          # 设置界面
│   ├── permissions.png       # 权限管理
│   ├── smart-recommendations.png # 智能推荐
│   ├── batch-comparison.png  # 批量比价
│   ├── dark-mode.png         # 夜间模式
│   ├── phone-small.png       # 小屏适配
│   ├── phone-large.png       # 大屏适配
│   ├── tablet.png            # 平板适配
│   ├── theme-blue.png        # 蓝色主题
│   ├── theme-green.png       # 绿色主题
│   └── theme-purple.png      # 紫色主题
├── qr-codes/                 # 二维码图片
│   ├── wechat-main-group.png # 微信主群二维码
│   ├── wechat-vip-group.png  # 微信VIP群二维码
│   └── qq-tech-group.png     # QQ技术群二维码
├── videos/                   # 演示视频文件
│   ├── installation-guide.mp4    # 安装教程
│   ├── quick-start.mp4           # 快速上手
│   ├── voice-comparison-demo.mp4 # 语音比价演示
│   ├── image-recognition-demo.mp4 # 图片识别演示
│   ├── floating-ball-demo.mp4    # 悬浮球功能演示
│   ├── price-analysis.mp4        # 价格分析教程
│   ├── personalization-settings.mp4 # 个性化设置
│   ├── batch-comparison.mp4      # 批量比价演示
│   ├── money-saving-tips.mp4     # 省钱技巧
│   ├── troubleshooting.mp4       # 问题解决教程
│   └── complete-workflow.mp4     # 完整流程演示
└── banners/                  # 宣传横幅图片
    ├── feature-banner.png    # 功能特色横幅
    ├── download-banner.png   # 下载引导横幅
    └── community-banner.png  # 社区宣传横幅
```

## 🎨 设计规范

### 📱 应用图标
- **主Logo**: 120x120px，PNG格式，透明背景
- **应用图标**: 多尺寸适配 (48x48, 72x72, 96x96, 144x144, 192x192)
- **设计风格**: 现代简约，符合Material Design规范
- **颜色主题**: 主色调为蓝色系 (#2196F3)

### 📸 截图规范
- **分辨率**: 1080x1920 (手机截图)
- **格式**: PNG格式，保证清晰度
- **内容**: 展示真实应用界面，避免模拟数据
- **标注**: 重要功能区域可添加标注说明

### 🎥 视频规范
- **分辨率**: 1080P (1920x1080)
- **格式**: MP4格式，H.264编码
- **帧率**: 30fps
- **音频**: AAC编码，清晰的解说音频
- **字幕**: 中文字幕，便于理解

### 📊 二维码规范
- **尺寸**: 200x200px
- **格式**: PNG格式
- **容错率**: 中等级别 (M级)
- **边距**: 周围留白至少10px

## 📋 文件命名规范

### 🖼️ 图片文件
- 使用小写字母和连字符
- 描述性命名，便于理解
- 例如: `home-screen.png`, `voice-input-interface.png`

### 🎬 视频文件
- 使用小写字母和连字符
- 包含功能描述和类型
- 例如: `voice-comparison-demo.mp4`, `installation-guide.mp4`

### 📱 图标文件
- 包含尺寸信息
- 例如: `icon-48x48.png`, `logo-120x120.png`

## 🔄 文件更新说明

### 📅 更新频率
- **截图**: 每次重大UI更新后更新
- **视频**: 每次功能更新后重新录制
- **Logo**: 品牌升级时更新
- **二维码**: 群组变更时更新

### 📝 版本管理
- 重要资源文件保留历史版本
- 使用日期后缀标识版本
- 例如: `logo-2024-12-15.png`

## 🎯 使用指南

### 📖 文档引用
在Markdown文档中引用资源文件时，使用相对路径：
```markdown
![TOMO Logo](assets/logo.png)
![主界面截图](assets/screenshots/home-screen.png)
```

### 🌐 网页使用
在网页中使用时，确保路径正确：
```html
<img src="assets/logo.png" alt="TOMO Logo" width="120">
```

### 📱 应用内使用
在应用开发中引用资源时，注意不同平台的路径规范。

## 📊 文件大小建议

| 文件类型 | 建议大小 | 最大限制 |
|----------|----------|----------|
| Logo/图标 | < 50KB | 100KB |
| 截图 | < 500KB | 1MB |
| 二维码 | < 20KB | 50KB |
| 横幅图片 | < 200KB | 500KB |
| 演示视频 | < 50MB | 100MB |

## 🔒 版权说明

### ✅ 自有资源
- 应用截图、Logo、图标等为TOMO团队原创
- 可用于官方宣传和文档说明
- 禁止第三方商业使用

### 📋 第三方资源
- 如使用第三方素材，需标注来源
- 确保符合相关授权协议
- 避免版权纠纷

### 🛡️ 使用限制
- 仅限TOMO项目相关用途
- 不得用于其他商业项目
- 转载需注明出处

## 📞 联系方式

如需更新或添加资源文件，请联系：
- 📧 设计团队: design@tomo-app.com
- 📧 技术团队: tech@tomo-app.com
- 💬 项目经理: pm@tomo-app.com

---

💡 **提示**: 本目录中的资源文件将在正式发布时添加。目前为占位符说明，帮助理解项目结构和资源组织方式。