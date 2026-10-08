[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/vibes-automation-auto-met/mikmoieklgpbgikeemkfffncmcmnhhab)

# 🚀 Vibes Automation v1.0.9 - Vibes.ai AI Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Vibes Automation** is a powerful Chrome extension designed to fully automate batch video and image generation on **Vibes.ai**. It allows you to run multiple prompts at scale, build and customize advanced workflows, and automatically download generated content — all with minimal manual effort.

-----

## ✨ Key Features

* **🚀 Batch Processing:** Queue dozens or hundreds of prompts and let the extension handle submission and generation automatically.
* **🧩 Workflow (visual drag-and-drop editor):** Connect prompts, images and generators on a canvas — e.g. generate images, then turn those images into videos automatically. Save several workflows, run one node or all of them, import/export them as files.
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

### 🧩 Workflow (Visual Drag-and-Drop Editor)

Workflow is a visual drag-and-drop editor for flows with several steps — for example: generate a few images, then use those images to make videos, then continue each video with another prompt. It opens in its own window and runs on your open vibes.ai tab.

#### Open it

* Click **Workflow** in the Control tab (bottom row).
* Already typed prompts or uploaded images in the side panel? Hover **Workflow** and click **Convert to workflow**: your prompts, each prompt's mode and your images become nodes in the editor, ready to run.

#### The screen

| Area | What it holds |
| :--- | :--- |
| **Left** | **Nodes** (click or drag one onto the canvas) and **Your workflows** (all saved workflows) |
| **Top bar** | The canvas tools: Undo/Redo, **Auto arrange**, fit view, **Example**, clear. On the right: the **Details** button, **Shortcuts** and the vibes.ai tab status |
| **Canvas** | Your nodes. Top-left: **Run all** (and **Stop** while running) and **Enable background mode** |

The **Details** button shows what needs attention: **Issues (n)** in red/yellow when something blocks a run, **Running 3/8** while generating. Click it to open a panel with the issues (click one to jump to the node), live progress, the run plan and the settings it uses.

#### Nodes

| Node | What it does |
| :--- | :--- |
| **Enter prompt** | One or more prompts, separated by a **blank line** |
| **Upload image** | Your images (drop files on it). Hover an image: 🔍 to view it larger, ✕ to remove it, the grip in the corner to drag it to another position. The order (or the sort menu) decides which prompt gets which image |
| **Generate Image** | Text to Image, or Image to Image when images are connected. Options: **Image Mode per Prompt**, **Max Input Images per Prompt**, **Auto-add character images** |
| **Generate Video** | Text to Video, or with images connected **Frame to Video** / **Components to Video**. Options: **Video Mode per Prompt**, images per prompt (shared with the side panel settings), **Auto-add character images** (Components to Video) |

Generate nodes are named automatically from their first prompt (`image_…` / `video_…`). Each prompt row shows the images it will receive, so you can check before running. Their preview takes the **aspect ratio** from the settings (a 9:16 node is narrower and taller).

**Frame to Video** can use a start frame only, or a **start frame and end frame** (same setting as the side panel). With start and end frame each prompt takes 2 images in order (a prompt continuing the previous video takes 1); if there are not enough images, the node shows a warning and can't run.

#### Connect nodes

Drag from the round handle on the right of a node and **drop it anywhere on the other node** — the right input is picked for you. Nodes that accept the connection light up while you drag.

| From | To | Meaning |
| :--- | :--- | :--- |
| Enter prompt | Generate Image / Generate Video | The prompts to generate |
| Upload image | Generate Image / Generate Video | Reference images, start frames or components |
| Generate Image | Generate Image / Generate Video | The **generated images** become that node's input (it runs after the images are ready) |
| Generate Video — **last frame** output | Generate Video | The next video **continues from the last frame** of this one |
| Generate Video — **last frame** output | Generate Image | The **last frame** of each video becomes an input image (it runs after the video is ready) |

#### Run

* **Run all** (top-left, or `Ctrl/⌘ + Enter`) runs the whole workflow in the right order: nodes waiting for generated images start automatically once those images exist.
* If **Run all** is disabled, the top bar shows **Issues (n)**: click it to see what to fix.
* Each Generate node also has its own **Run** button to run only that node. It is disabled until the nodes it depends on have finished (hover to see why).
* **Stop** cancels what is still running.
* While running, the connections into the node that is generating light up and flow, so you can see where the workflow is.

> ⚠️ **Chrome pauses vibes.ai when its tab isn't visible** (for example when the workflow window covers it full screen). Click **Enable background mode** (under **Run all** in the workflow, or in the side panel), then pick the vibes.ai tab in Chrome's dialog. This shares the vibes.ai tab (nothing is recorded or sent anywhere) so it keeps generating behind other windows. The green **Running in background** badge shows it's on; click ✕ to stop it.

#### Results

Results appear inside each Generate node. Hover a result: 🔍 opens it large, ✕ removes it (the eraser clears all results of the node). Videos play on hover. Files are still downloaded as usual.

The next node uses the **first result of each prompt**. To choose which one, drag a result by the grip in its top-left corner onto another result to swap them (images and videos).

#### Manage workflows

Under **Your workflows** (left): **New**, **Import**, and for each workflow the **⋯** menu — **Rename** (or double-click the name), **Duplicate**, **Export**, **Delete**. Everything is saved automatically.

* **Export** downloads a `.json` file. It starts with `//` comment lines that describe every node, property and connection, so you can give the file to an AI assistant and ask it to write new workflows. The comment lines are removed on import.
* **Import** a file with the button, or simply **drag the `.json` file onto the canvas**.

#### Editing shortcuts

Click **Shortcuts** in the top bar (or press `?`) to see them all.

| Action | Keys |
| :--- | :--- |
| Undo / Redo | `Ctrl/⌘ + Z` / `Ctrl/⌘ + Shift + Z` |
| Copy / Cut / Paste nodes (also into another workflow) | `Ctrl/⌘ + C / X / V` |
| Duplicate selection | `Ctrl/⌘ + D` |
| Select all / Add to selection / Box select | `Ctrl/⌘ + A` / `Ctrl/⌘ + click` / `Shift + drag` |
| Auto arrange | `Shift + A` |
| Delete selected | `Delete` |
| Run all / Run in background | `Ctrl/⌘ + Enter` / `Ctrl/⌘ + Shift + Enter` |

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
| **Workflow: generation stays at "Generating" forever** | Chrome paused the hidden vibes.ai tab. Turn on **Enable background mode** (or **Run in background**), or keep vibes.ai visible. |
| **Workflow: a node's Run button is disabled** | Hover it: run the node it depends on first, or fix the issue shown (e.g. no prompt connected). |
| **Workflow: Run all is disabled** | Click **Issues (n)** in the top bar to see what to fix; click an issue to jump to its node. |
| **Workflow: "No vibes.ai tab found"** | Open [vibes.ai](https://vibes.ai) in a tab (the green dot in the top bar shows it's connected). |

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
