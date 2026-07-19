[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/vibes-automation-auto-met/mikmoieklgpbgikeemkfffncmcmnhhab)

# 🚀 Vibes Automation v1.0.9 - Vibes.ai AI Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Vibes Automation** is a powerful Chrome extension designed to fully automate batch video and image generation on **Vibes.ai**. It allows you to run multiple prompts at scale, build and customize advanced workflows, and automatically download generated content — all with minimal manual effort.

-----

## ✨ Key Features

* **🚀 Batch Processing:** Queue dozens or hundreds of prompts and let the extension handle submission and generation automatically.
* **🎬 Text-to-Video Automation:** Generate videos from text descriptions. Supports batch processing with custom delays.
* **🎬 Frame-to-Video:** Use a static image (Start frame, or Start + End frames) and prompts to create dynamic videos with automatic motion effects.
* **🎬 Ingredients-to-Video:** Animate UI components, characters, and interface elements into video. Support uploading multiple images (up to 10 images).
* **🖼️ Text-to-Image Batching:** Create multiple images with support for aspect ratios: 16:9 (YouTube), 9:16 (Shorts/Reels), 1:1 (Square), 2:3 (Portrait), 3:2 (Landscape).
* **🖼️ Image-to-Image:** Transform and enhance images using AI with text prompts.
* **⚙️ Professional Controls:**
    * **Concurrent Prompts:** Process multiple prompts at once to save time.
    * **Random Delays:** Set custom random wait times between prompts to manage rate limits and mimic human behavior.
    * **Auto Download Quality:** Automatically download results when generation completes. Supports video qualities (480p, 720p, or no-download) and image qualities (1k, or no-download).
    * **Auto-add Character Images:** Automatically match and attach uploaded images that match character names referenced in prompts (based on filenames).
    * **Smart Chaining & Video Concat:** Chain prompts together: use "5s concat" to automatically combine consecutive generations into one video, or "Edit Image" to reuse the last generated output as input for the next prompt.
* **📊 Real-time Queue Monitoring:** Monitor progress with a visual status bar, active prompt list, and detailed logs in the Side Panel.
* **📂 Organized File Management:** Downloads are automatically sorted into project-based subfolders.
* **🌐 Multi-language Support:** English, Spanish, Japanese, Korean, Vietnamese, Chinese.

-----

## 📥 Installation

### Method 1: Chrome Web Store (Recommended)
1. Visit the [Chrome Web Store](https://chromewebstore.google.com/detail/vibes-automation-auto-met/mikmoieklgpbgikeemkfffncmcmnhhab) and click **Add to Chrome**.

---

## 📖 User Guide

### Getting Started

1. **Navigate to Vibes.ai**
   - Open [vibes.ai/projects](https://www.vibes.ai/projects) (or [vibes.ai](https://vibes.ai))
   - The extension works on Vibes.ai workspace/projects pages.

2. **Open the Extension**
   - Click the extension icon in the Chrome toolbar. Pin it for easier access!

3. **Configure Batch Settings**
   - In the **Control** tab, you can set:
     - **Save to folder:** Subfolder name inside Chrome's downloads folder for this project.
     - **Auto change file name:** Automatically renames files sequentially (e.g., `001_prompt_a.mp4`).
   - In the **Setting** tab, configure:
     - **Concurrent Prompts:** How many prompts to process simultaneously.
     - **Random Delay:** Wait time between prompt submissions.
     - **Auto Download Quality:** Set video quality (480p/720p) or image quality (1k).

4. **Select a Mode**
   - Choose from: **Text to Video**, **Frame to Video**, **Ingredients to Video**, **Text to Image**, or **Image to Image**.

---

### 1. Text-to-Video Mode

1. Select **Text to Video** mode.
2. Enter prompts into the input box (separate each prompt with a **blank line**).
3. Alternatively, click the **Upload** icon to import prompts from a `.txt`, `.xlsx`, or `.csv` file.
4. Click **Run** to start the batch.

**Example Prompt:**
```
A futuristic cyberpunk city with neon lights reflecting in the rain.
The camera glides through the narrow alleys.

A peaceful Japanese garden with cherry blossoms falling into a pond.
A slow zoom into the koi fish swimming below.
```

### 2. Frame-to-Video Mode (Image-to-Video)

1. Select **Frame to Video** mode.
2. Click to upload or drag & drop one or two static images (Start frame / End frame based on Settings).
3. Enter prompts (separate with blank lines). The uploaded images will be processed with each prompt.
4. Click **Run**.

### 3. Ingredients-to-Video Mode

1. Select **Ingredients to Video** mode.
2. Upload UI components, character layers, or reference images (up to 10 images).
3. Enter prompts detailing the scene actions and animations.
4. (Optional) Enable **Auto-add character images** to automatically attach uploaded images that match character names mentioned in the prompt (matching by filename).
5. Click **Run**.

### 4. Text-to-Image Mode

1. Select **Text to Image** mode.
2. Enter detailed descriptions for your images (separated by a blank line).
3. Configure the desired **Aspect Ratio** (16:9, 9:16, 1:1, 2:3, 3:2) and **Outputs Image per Prompt** in the Settings tab.
4. Click **Run**.

### 5. Image-to-Image Mode

1. Select **Image to Image** mode.
2. Upload one or more source images.
3. Enter prompts for image variations or enhancements.
4. Click **Run**.

---

## ⚙️ Settings Configuration

Access the **Setting** tab to customize your experience:

* **Default Mode:** Set which mode opens by default.
* **Default Aspect Ratio:** Choose from 16:9, 9:16, 1:1, 2:3, or 3:2.
* **Outputs per Prompt:** Set how many videos to generate per prompt (min 1, max 4).
* **Outputs Image per Prompt:** Set how many images to generate per prompt (min 1, max 50).
* **Concurrent Prompts:** Set number of concurrent generations (1 to 6 prompts).
* **Random Delay:** Configure random intervals between prompts to avoid rate limits.
* **Video/Image Model:** Select the generation model to use.
* **Default Video Option:** Choose between "5 seconds" and "5 seconds (concat)" duration.
* **Default Image Option:** Choose between "New Image" and "Edit Image" (reuse previous output).
* **Max Retries on Failure:** Specify retry attempts (1 to 20) if a generation fails.
* **Auto Download Quality:** Set preferred video (480p/720p/no-download) or image (1k/no-download) quality.
* **Language:** Switch between English, Tiếng Việt, 中文, 한국어, 日本語, Español.

---

## 💡 Tips & Best Practices

1. **Rate Limits:** If you encounter rate limits or platform errors, increase the **Random Delay** in the Settings tab and decrease **Concurrent Prompts** to 1.
2. **Spreadsheet Imports:** When uploading spreadsheets (`.xlsx`/`.csv`), you can preview the rows and select the exact column containing your prompts to import.
3. **Smart Concat:** Use "5s concat" for videos or "Edit Image" for image-to-image chains to create continuous storyboards or progressive variations.
4. **File Renaming:** Keep **Auto change file name** checked so that all downloaded resources are cleanly numbered (e.g. `001_...`, `002_...`) for chronological tracking.

---

## 🔧 Troubleshooting

| Issue | Solution |
| :--- | :--- |
| **Extension not active** | Ensure you are on [vibes.ai](https://vibes.ai) or [vibes.ai/projects](https://www.vibes.ai/projects). Refresh the page if needed. |
| **Connection Error** | Press F5 / Ctrl+R to refresh the page. Re-open the extension side panel. |
| **Generation Errors** | The extension will automatically retry failed prompts up to the configured **Max Retries** in Settings. Click **Fix Error** to quickly reset if stuck. |
| **Downloads not working** | Ensure "Ask where to save each file before downloading" is **OFF** in Chrome Settings (`chrome://settings/downloads`). |
| **Login Required** | Ensure you are logged into both your Vibes.ai account on the webpage and your Max plan account in the extension. |

---

## 🔒 Privacy & Data

* **Local Processing:** All automation logic runs locally in your browser.
* **No Data Collection:** We do not store or collect your prompts, images, or account data.
* **Secure Storage:** Settings are saved only in your browser's local/sync storage.

---

## 📞 Support

- **Author:** Trường Nguyễn
- **Email:** kylenguyenaws@gmail.com
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Feedback:** Use the "Report Bug" link in the extension tab to copy debug logs and contact support.

---

## 📦 Version

Current version: **1.0.9**

---

## 📜 License

Copyright © 2026 **Trường Nguyễn**. All Rights Reserved.

This software is proprietary. Unauthorized copying or distribution is prohibited.

---

**Made with ❤️ by Trường Nguyễn**
