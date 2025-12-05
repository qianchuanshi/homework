# 素材文件夹说明

## 文件夹结构

```
assets/
├── images/      # 图片素材
│   └── wechat-qrcode.jpg  # 微信二维码
├── audio/       # 音频素材（录音、音乐等）
└── videos/     # 视频素材
```

## 使用方法

### 图片引用
在 HTML/React 代码中引用图片：
```jsx
// 相对路径引用
<img src="./assets/images/wechat-qrcode.jpg" alt="描述" />

// 或使用绝对路径（根据项目结构调整）
<img src="/assets/images/your-image.jpg" alt="描述" />
```

### 音频引用
```jsx
<audio src="./assets/audio/your-audio.mp3" controls />
```

### 视频引用
```jsx
<video src="./assets/videos/your-video.mp4" controls />
```

## 文件命名建议

- **图片**：使用有意义的名称，如 `hero-banner.jpg`, `logo.png`, `icon-svg.svg`
- **音频**：如 `podcast-episode-1.mp3`, `background-music.mp3`
- **视频**：如 `demo-video.mp4`, `tutorial.mp4`

## 注意事项

- 保持文件名简洁，避免特殊字符和空格
- 建议使用小写字母和连字符（-）或下划线（_）
- 图片格式推荐：`.jpg`（照片）、`.png`（透明背景）、`.svg`（图标）
- 音频格式推荐：`.mp3`（兼容性好）、`.wav`（高质量）
- 视频格式推荐：`.mp4`（兼容性好）

