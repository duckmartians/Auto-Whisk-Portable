# 🎨 Auto Whisk Generator  
**Whisk AI Automation Tool**

Auto Whisk Generator automates the entire image-creation workflow on Whisk AI (Google Labs).  
Instead of manually entering prompts one by one, the tool allows continuous, hands-free generation of thousands of images.

---

## 🛠️ Install the "Cookie Exporter" Extension

To operate, the tool requires your Whisk session Cookie. Install the extension that exports your Cookie:

**Download Extension:**  
[Cookie Exporter – Chrome Web Store](https://chromewebstore.google.com/detail/fhnmmidekmgocpjdceeffppcodigillk)

**Steps:**
1. Open the link in Chrome or Edge.  
2. Click **Add to Chrome**.  
3. A duck icon 🦆 appears in the browser toolbar (pin it if hidden).

---

## 🍪 Export Cookie from Whisk AI

1. Visit https://labs.google/fx/tools/whisk  
2. Sign in with your Google account.  
3. Click the **Cookie Exporter** icon.  
4. In *Export format*, select **JSON**.  
5. Click **Copy** to copy the Cookie string.

This JSON Cookie will be used for token extraction.

---

## 🚀 Run the Auto Whisk Tool

The tool is packaged as a `.exe` file. No Python installation required.

1. Download the compressed package.  
2. Extract it.  
3. Run **AutoWhiskGenerator.exe**.

---

## 📖 How to Use the Tool

The interface is divided into three clear steps.

---

### 🅰️ Step A: Retrieve Data (Token)

1. In **Retrieve Data (Token/Workflow ID)**:  
   - Paste the JSON Cookie into the input box.  
2. Enable **Headless Mode**.  
3. Click **🚀 GET NEW DATA**.  
4. Wait 10–30 seconds while the tool processes.

**Success:** A green message appears: **“Token retrieved successfully!”** along with its expiration time.

---

### 🅱️ Step B: Configure Image Generation

**Aspect Ratio & Quantity:**  
- Choose 16:9, 9:16, or 1:1.  
- Select the number of images per prompt (1–4).

**Prompt List:**  
- Enter prompts line by line (one prompt per line).

**Save Directory:**  
- Default: `output` folder next to the `.exe`.  
- Change via 📂 if desired.

---

### 🅾️ Step C: Run & Monitor

1. Click **START NEW**.  
2. The tool will automatically send prompts, wait for generation, and download each image.  
3. Progress and previews are displayed live.

---

## 💡 Advanced Features

- **⏯️ Resume/Pause:** Pause anytime and continue later without losing progress.  
- **🔄 Retry:** Retry failed generations (single items or all).  
- **🔍 Viewer:** Click thumbnails to view full-size images.  
- **📂 Management:** Open the output folder or delete failed images directly.  
- **☕ Donate:** Support the developer via **[☕ Buy Me a Coffee](https://duckmartians.info)**.

---

## ⚠️ Important Notes

- **Token Expiration:** Whisk tokens typically last around one day. When expired, repeat Step A.  
- **Security:** Never share your Cookie with anyone.

---

Create incredible artwork effortlessly! 🎨
