[![点击这里下载](https://img.shields.io/badge/⬇_下载-点击这里-success?style=for-the-badge)](https://chromewebstore.google.com/detail/vibes-automation-auto-met/mikmoieklgpbgikeemkfffncmcmnhhab)

# 🚀 Vibes 自动化 v1.0.9 - Vibes.ai AI 自动化 [![English](https://img.shields.io/badge/English-blue)](README.md) [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md)

**Vibes Automation** 是一款强大的 Chrome 扩展程序，旨在完全自动化 **Vibes.ai** 平台上的批量视频和图像生成。它允许您大规模运行多个提示词，构建和自定义高级工作流程，并自动下载生成的内容 —— 所有这一切只需极少的人工干预。

-----

## ✨ 主要功能

* **🚀 批处理：** 排队数十或数百个提示词，让扩展程序自动提交和生成。
* **🎬 文本转视频自动化：** 从文本描述生成视频。支持带自定义延迟的批处理。
* **🎬 帧转视频 (Frame-to-Video)：** 使用单张静态图片（起始帧，或设置起始帧+结束帧）和提示词创建具有自动动态效果的视频。
* **🎬 原料/成分转视频 (Ingredients-to-Video)：** 将UI组件、角色图层或参考图片制作为视频。支持上传多张图片（最多 10 张）。
* **🖼️ 文本转图片批处理：** 创建多张图片，支持丰富的宽高比：16:9 (YouTube)、9:16 (Shorts/Reels)、1:1 (Square)、2:3 (Portrait)、3:2 (Landscape)。
* **🖼️ 图片转图片：** 根据文本提示词使用 AI 转换和增强图像。
* **⚙️ 专业控制：**
    * **并发 Prompt：** 同时处理多个提示词以节省时间。
    * **随机延迟：** 设置自定义的随机等待时间，以管理频率限制并模拟人工行为。
    * **自动下载质量：** 在生成完成时自动下载结果。支持视频质量选项（480p、720p 或不下载）以及图片质量选项（1k 或不下载）。
    * **自动添加角色图像：** 根据文件名，自动匹配并附加与提示词中提到的角色名称对应的已上传图像。
    * **智能链式生成与视频拼接：** 将提示词链接在一起：使用 "5s concat" 自动将连续生成的视频合并为一个视频，或选择 "编辑图像"（Edit Image）将上一次生成的图片用作下一个提示词的输入。
* **📊 实时队列监控：** 通过侧边面板中的直观状态栏、活跃提示词列表和详细日志监控进度。
* **📂 有序文件管理：** 下载内容按项目自动分类到文件夹中。
* **🌐 多语言支持：** 英语、西班牙语、日语、韩语、越南语、中文。

-----

## 📥 安装

### 方法 1：Chrome 网上应用店（推荐）
1. 访问 [Chrome 网上应用店](https://chromewebstore.google.com/detail/vibes-automation-auto-met/mikmoieklgpbgikeemkfffncmcmnhhab) 并点击 **添加至 Chrome**。

---

## 📖 使用指南

### 开始使用

1. **访问 Vibes.ai**
   - 打开 [vibes.ai/projects](https://www.vibes.ai/projects)（或 [vibes.ai](https://vibes.ai)）
   - 扩展程序在 Vibes.ai 的项目/工作区页面上运行。

2. **打开扩展程序**
   - 点击 Chrome 工具栏中的扩展程序图标。建议固定以便快速访问！

3. **配置批量设置**
   - 在 **控制 (Control)** 标签页中可以设置：
     - **Save to folder:** Chrome 下载文件夹内用于存放该项目的子文件夹名称。
     - **Auto change file name:** 自动按顺序重命名下载的文件（例如：`001_prompt_a.mp4`）。
   - 在 **设置 (Setting)** 标签页中配置：
     - **Concurrent Prompts:** 同时运行的提示词数量。
     - **Random Delay:** 每次提交提示词之间的随机等待时间。
     - **Auto Download Quality:** 设置视频下载质量 (480p/720p) 或图片下载质量 (1k)。

4. **选择模式**
   - 可选模式：**Text to Video** (文本转视频)、**Frame to Video** (帧转视频)、**Ingredients to Video** (成分转视频)、**Text to Image** (文本转图片) 或 **Image to Image** (图片转图片)。

---

### 1. 文本转视频模式 (Text-to-Video)

1. 选择 **Text to Video** 模式。
2. 在输入框中输入提示词（每个提示词之间用 **空行** 分隔）。
3. 或者点击 **上传** 图标从 `.txt`、`.xlsx` 或 `.csv` 文件导入提示词列表。
4. 点击 **Run** 开始批处理。

**示例提示词：**
```
一个充满霓虹灯的未来派赛博朋克城市，雨水倒映着灯光。
摄像机穿过狭窄的小巷。

一个宁静的日本花园，樱花飘落进池塘。
摄像机缓慢放大观察下方游动的锦鲤。
```

### 2. 帧转视频模式 (Frame-to-Video)

1. 选择 **Frame to Video** 模式。
2. 点击上传或拖放一张或两张静态图片（根据设置的起始帧 / 结束帧）。
3. 输入提示词（用空行分隔）。上传的图片将与每个提示词结合处理。
4. 点击 **Run**。

### 3. 成分转视频模式 (Ingredients-to-Video)

1. 选择 **Ingredients to Video** 模式。
2. 上传界面组件、角色图层或参考图片（最多支持 10 张图片）。
3. 输入详细描述场景动作和动画的提示词。
4. (可选) 启用 **Auto-add character images**，系统将根据文件名自动关联提示词中提到的角色对应图片。
5. 点击 **Run**。

### 4. 文本转图片模式 (Text-to-Image)

1. 选择 **Text to Image** 模式。
2. 输入图片的详细描述（用空行分隔）。
3. 在设置标签页中配置所需的 **宽高比** (16:9, 9:16, 1:1, 2:3, 3:2) 和 **每个提示词生成的图片数量**。
4. 点击 **Run**。

### 5. 图片转图片模式 (Image-to-Image)

1. 选择 **Image to Image** 模式。
2. 上传一张或多张源图片。
3. 输入用于图片变体或画质提升的提示词。
4. 点击 **Run**。

---

## ⚙️ 设置配置

访问 **设置 (Setting)** 标签页来自定义您的体验：

* **Default Mode:** 设置默认开启的模式。
* **Default Aspect Ratio:** 选择默认的宽高比（16:9, 9:16, 1:1, 2:3 或 3:2）。
* **Outputs per Prompt:** 设置每个视频提示词生成的视频数量（最小 1，最大 4）。
* **Outputs Image per Prompt:** 设置每个图片提示词生成的图片数量（最小 1，最大 50）。
* **Concurrent Prompts:** 设置同时处理的提示词并发数（1 至 6 个提示词）。
* **Random Delay:** 配置提示词提交之间的随机时间间隔，以避免速率限制。
* **Video/Image Model:** 选择用于生成内容的 AI 模型。
* **Default Video Option:** 选择默认视频时长为 "5 seconds" 还是 "5 seconds (concat)"。
* **Default Image Option:** 选择图片输入模式为 "New Image"（新图片）还是 "Edit Image"（编辑上一张生成的图片）。
* **Max Retries on Failure:** 指定在生成失败时的最大重试次数（1 至 20 次）。
* **Auto Download Quality:** 设置首选的视频（480p/720p/不下载）或图片（1k/不下载）下载画质。
* **Language:** 切换界面语言（English, Tiếng Việt, 中文, 한국어, 日本語, Español）。

---

## 💡 提示与最佳实践

1. **频率限制 (Rate Limits)：** 如果遇到频率限制或平台报错，请增加设置中的 **Random Delay** 并将 **Concurrent Prompts** 降为 1。
2. **导入表格文件：** 在导入表格 (`.xlsx`/`.csv`) 时，您可以预览数据行并选择要导入的提示词所在的特定列。
3. **智能链式拼接：** 对于视频使用 "5s concat"，或者对图片使用 "Edit Image" 来创建连续的故事情节或逐步演变的效果。
4. **文件重命名：** 保持勾选 **Auto change file name**，以确保下载的所有资源按时间顺序进行完美编号（例如 `001_...`，`002_...`）。

---

## 🔧 故障排除

| 问题 | 解决方案 |
| :--- | :--- |
| **扩展程序未激活** | 确保您位于 [vibes.ai](https://vibes.ai) 或 [vibes.ai/projects](https://www.vibes.ai/projects)。如果需要，请刷新页面。 |
| **连接错误** | 按 F5 / Ctrl+R 刷新页面，然后重新打开扩展的侧边栏。 |
| **生成错误** | 扩展程序会自动重试失败的提示词，最高达到在设置中配置的 **Max Retries** 次数。如果卡住，点击 **Fix Error** 可以快速重置。 |
| **下载无效** | 确保在 Chrome 设置中 **关闭** 了“下载前询问每个文件的保存位置” (`chrome://settings/downloads`)。 |
| **需要登录** | 请确保已登录网页端的 Vibes.ai 账户以及扩展程序中的 Max 计划账户。 |

---

## 🔒 隐私与数据

* **本地处理：** 所有自动化逻辑均在您的浏览器中本地运行。
* **无数据收集：** 我们不存储或收集您的提示词、图像或账户数据。
* **安全存储：** 设置仅保存在您浏览器的本地存储/同步存储中。

---

## 📞 支持

- **作者：** Trường Nguyễn
- **邮箱：** kylenguyenaws@gmail.com
- **网站：** [kylenguyen.me](https://kylenguyen.me)
- **反馈：** 使用扩展程序中的“Report Bug”链接复制调试日志并联系支持团队。

---

## 📦 版本

当前版本：**1.0.9**

---

## 📜 版权声明

版权所有 © 2026 **Trường Nguyễn**。保留所有权利。

本软件为专有财产。未经授权，严禁复制或分发。

---

**由 Trường Nguyễn 用 ❤️ 制作**
