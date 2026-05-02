# 浪漫表白界面 - 使用说明

## 如何添加背景音乐

1. 获取光良演唱的歌曲《窗外》的MP3文件
2. 将MP3文件重命名为 `chuangwai.mp3`
3. 将文件放在与 `love.html` 相同的目录下

## 目录结构

```
qianduan_demo/
├── love.html          # 表白界面主文件
├── chuangwai.mp3      # 背景音乐文件（需自行添加）
└── README.md          # 本说明文件
```

## 自定义表白内容

打开 `love.html` 文件，找到以下部分进行修改：

- **标题**：搜索 `致我最爱的你` 修改标题文字
- **表白内容**：搜索 `<div class="letter-content">` 修改表白文字
- **签名**：搜索 `永远爱你的我` 修改签名

## 运行方式

直接双击 `love.html` 文件即可在浏览器中打开，或使用本地服务器运行：

```bash
python -m http.server 8080
```

然后访问 http://localhost:8080/love.html
