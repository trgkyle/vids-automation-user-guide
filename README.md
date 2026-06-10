[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/vids-automation-auto-veo/caiompjhmpmodfbfdbihlkbbeijgpial)

# 🚀 Vids Automation v1.0.0 - Google Vids AI Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Vids Automation** is a productivity extension that automates your creative workflow on Google Vids (docs.google.com/videos). Stop manually entering prompts one by one—automate the process and generate videos, images, and voice-overs at scale.

-----

## ✨ Key Features

* **🚀 Batch Processing:** Queue dozens or hundreds of prompts and let the extension handle submission and generation automatically.
* **🎬 Text-to-Video (Auto VEO & Nano Banana):** Generate high-quality videos from text descriptions.
* **🎬 Frame-to-Video (Image-to-Video):** Convert a static image frame into a dynamic video with motion prompt controls.
* **🎬 Ingredients-to-Video (Components-to-Video):** Animate user interface components and layouts. Supports uploading up to **3 images** per prompt.
* **🖼️ Text-to-Image Batching:** Generate multiple high-quality images with customized aspect ratios (16:9, 9:16, 1:1, 2:3, 3:2).
* **🎙️ Text-to-Voice:** Convert paragraphs of text into spoken audio tracks with custom download quality settings.
* **⚙️ Professional Controls:**
    * **Prompt Delay Range:** Set custom minimum and maximum intervals between prompts to manage rate limits.
    * **Auto Download:** Automatically download your generated assets (videos, images, or audio) in high quality when done.
    * **Output Count Restriction:** Strict support for max 1 output per prompt run to maximize efficiency.
* **📊 Real-time Queue Monitoring:** Track batch jobs with a progress queue and active prompt indicator in the Side Panel.
* **📂 Organized File Management:** Auto-download files are systematically saved into project-based subfolders.
* **🌐 Multi-language Support:** English, Vietnamese, Chinese, Korean, Japanese, Spanish.

-----

## 📥 Installation

### Method 1: Chrome Web Store (Recommended)
1. Visit the [Chrome Web Store](https://chromewebstore.google.com/detail/vids-automation-auto-veo/caiompjhmpmodfbfdbihlkbbeijgpial)
2. Click **Add to Chrome**.

### Method 2: Local Developer Mode
1. Download or clone this repository to your local machine.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Toggle the **Developer mode** switch in the top-right corner.
4. Click **Load unpacked** and select the extension build folder (`dist/chrome`).

-----

## 📖 User Guide

### Getting Started

1. **Navigate to Google Vids**
   - Open [docs.google.com/videos](https://docs.google.com/videos)
   - Ensure you are logged into your Google Account.

2. **Open the Extension**
   - Click the extension icon in the Chrome toolbar. Pin it for easier access!

3. **Configure Batch Settings**
   - In the **Control** tab, you can set the **Prompt Delay** (min/max wait time between prompt submissions).

4. **Select a Mode**
   - Choose from: **Text to Video**, **Frame to Video**, **Ingredients to Video**, **Text to Image**, or **Text to Voice**.

### 1. Text-to-Video Mode

1. Select **Text to Video** mode.
2. Enter prompts into the input box (separate each prompt with a **blank line**).
3. Alternatively, click the **Upload** buttons to import prompts from a `.txt` file or `.xlsx` / `.csv` spreadsheets.
4. Click **Run** to start the batch.

**Example Prompt:**
```
A futuristic cyberpunk city with neon lights reflecting in the rain.
The camera glides through the narrow alleys.

A peaceful Japanese garden with cherry blossoms falling into a pond.
A slow zoom into the koi fish swimming below.
```

### 2. Frame-to-Video Mode

1. Select **Frame to Video** mode.
2. Drag & drop or upload a starting image.
3. Enter prompts describing the motion (separated by blank lines).
4. Click **Run**.

### 3. Ingredients-to-Video Mode

1. Select **Ingredients to Video** mode.
2. Upload component image frames (supports up to **3 images** per prompt).
3. Enter prompts detailing how the components animate.
4. Click **Run**.

### 4. Text-to-Image Mode

1. Select **Text to Image** mode.
2. Enter detailed prompts separated by blank lines.
3. Choose the **Aspect Ratio** and **Image Model** configurations in the Settings tab.
4. Click **Run**.

### 5. Text-to-Voice Mode

1. Select **Text to Voice** mode.
2. Enter paragraphs of voice script separated by blank lines.
3. Click **Run**.
4. In the Settings tab, you can customize the default voice chaining (`defaultAudioOption`) and audio download options.

---

## ⚙️ Settings Configuration

Access the **Settings** tab to customize your automation workflow:

* **Default Mode:** Set which tab opens by default.
* **Aspect Ratio:** Choose default aspect ratio (16:9, 9:16, 1:1, 2:3, 3:2).
* **Default Video Option:** Default duration configuration (5s or 5s-concat).
* **Default Image Option:** Default input mode for image prompts (New Image or Edit Image).
* **Default Audio Option:** Default duration/concat mode for audio prompts (Create new or Combine Audio).
* **Auto Download Video Quality:** Choose download resolutions (No download, 480p, 480p-upscale, 720p).
* **Auto Download Image Quality:** Choose download resolutions (No download, 1k).
* **Auto Download Audio Quality:** Choose download formats (No download, Original MP3).
* **Auto Change File Name:** Automatically rename files to match folders and prefixes.
* **Folder Name:** Define a subfolder in your Downloads directory to keep files organized.
* **Max Retries:** Set how many times the extension should retry on generation failures.

---

## 💡 Tips & Best Practices

1. **Smart Delays:** If you run into speed limits or generation blocks, increase the **Prompt Delay** ranges.
2. **Download Locations:** Make sure you turn off Chrome's prompt for download locations (see below) to let files download automatically.
3. **Workspace Organization:** Always define a custom **Folder Name** in Settings before launching a large batch to avoid cluttering your default Downloads directory.

---

## 🔧 Troubleshooting

| Issue | Solution |
| :--- | :--- |
| **Extension not active** | Ensure you are on [docs.google.com/videos](https://docs.google.com/videos). Refresh the page if needed. |
| **Downloads prompt popup** | In Chrome Settings under Downloads, turn **OFF** "Ask where to save each file before downloading". |
| **Generation Errors** | Google Vids may be throttled. The extension will automatically retry the prompt up to the configured **Max Retries** count. |
| **Login Required** | Ensure you are logged into your active Google Workspace or Google Account with Google Vids access. |

---

## 🔒 Privacy & Data

* **Local Processing:** All automation commands are executed locally in your browser.
* **No Data Harvesting:** We do not harvest, store, or monitor your prompts, images, or account configurations.
* **Secure Storage:** Settings are saved directly within Chrome's local storage engine.

---

## 📞 Support

- **Author:** Trường Nguyễn
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Feedback:** Use the "Report a bug" link in the extension.

---

## 📦 Version

Current version: **1.0.0**

---

## 📜 License

Copyright © 2026 **Trường Nguyễn**. All Rights Reserved.

This software is proprietary. Unauthorized copying or distribution is prohibited.

---

**Made with ❤️ by Trường Nguyễn**
