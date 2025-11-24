# 🎨 Auto Whisk Generator  [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![English](https://img.shields.io/badge/English-blue)](README.md) 
[![Download for Windows](https://img.shields.io/badge/Download%20for%20Windows-%F0%9F%92%BB-blue?style=for-the-badge)](https://github.com/duckmartians/Auto-Whisk-Portable/releases/latest) [![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://github.com/duckmartians/Auto-Whisk-Portable/releases/latest)

Auto Whisk Generator automates the entire image-creation workflow on Whisk AI (Google Labs).  
Instead of manually entering prompts one by one, the tool allows continuous, hands-free generation of thousands of images.
<img width="2166" height="1032" alt="image" src="https://github.com/user-attachments/assets/c2560244-813a-4717-8543-e6eb417d5589" />

---

## 🛠️ Install the "Cookie Exporter" Extension

To operate, the tool requires your Whisk session Cookie. Install the extension that exports your Cookie:

**Download Extension:**  
[Cookie Exporter – Chrome Web Store](https://chromewebstore.google.com/detail/fhnmmidekmgocpjdceeffppcodigillk)
<img width="1130" height="215" alt="image" src="https://github.com/user-attachments/assets/e20c7343-b16f-4dff-a2ef-33f1f2d624e9" />

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
<img width="1919" height="502" alt="image" src="https://github.com/user-attachments/assets/865798c4-092f-47b9-b5f3-70823cf3ecbe" />

This JSON Cookie will be used for token extraction.

---

## 🚀 Run the Auto Whisk Tool

The tool is packaged as a `.exe` file. No Python installation required.

1. Download the compressed package **Auto.Whisk.Generator.v24.11.2025.zip**.  
2. Extract it.  
3. Run **Auto Whisk Generator v24.11.2025.exe**.

## ⚠️ IMPORTANT NOTE: IF BLOCKED BY WINDOWS DEFENDER

If you open the tool and Windows reports a virus error (usually Trojan:Win32/Wacatac...), please don't worry. This is a FALSE ALARM (False Positive).

Why is there an error?
The tool is packaged with the free tool PyInstaller. Because I am an individual programmer, I do not buy a "Digital Signature" (an expensive license that big companies use to prove that software is safe) for the tool, so Windows Defender will block it by default because it "sees a stranger", cannot identify the identity.

Safety commitment:
1. Open source tool, only performs automatic operations on the browser, absolutely does not contain malicious code.

2. Specialized anti-virus software (such as Kaspersky, ESET...) all confirm that this file is CLEAN.

How to fix:
To use, please add the tool file to the exclusions list or temporarily turn off Windows Defender Real-time protection.

---

## 📖 How to Use the Tool

The interface is divided into three clear steps.

---

### 🅰️ Step A: Retrieve Data (Token)

1. In **Retrieve Data (Token/Project)**:  
   - Paste the JSON Cookie into the input box.  
2. Click **🚀 GET NEW DATA**.  
3. Wait 10–30 seconds while the tool processes.
<img width="392" height="250" alt="image" src="https://github.com/user-attachments/assets/79088390-0cde-43be-bfd7-b40040ecd65b" />

**Success:** A green message appears: **“Token retrieved successfully!”** along with its expiration time.

---

### 🅱️ Step B: Configure Image Generation

**Aspect Ratio & Quantity:**  
- Choose 16:9, 9:16, or 1:1.  
- Select the number of images per prompt (1–4).
<img width="379" height="106" alt="image" src="https://github.com/user-attachments/assets/ce9e88c3-e9f6-46d6-8481-9527116181b1" />

**Reference photos:**
- Select subject, background, style.
- Can use 3 subject photos, 1 background photo, 1 style photo at the same time.
<img width="866" height="463" alt="image" src="https://github.com/user-attachments/assets/3e5bce2a-e484-4da2-b487-4474f192f7f5" />

**Prompt List:**  
- Enter prompts line by line (one prompt per line).
<img width="381" height="145" alt="image" src="https://github.com/user-attachments/assets/9d49cf07-edb1-4740-9ecb-73c3c798d33e" />

**Save Directory:**  
- Default: `output` folder next to the `.exe`.  
- Change via 📂 if desired.
<img width="389" height="83" alt="image" src="https://github.com/user-attachments/assets/f9d8350a-8c5d-4f22-8434-ca9d738c0cc7" />

---

### 🅾️ Step C: Run & Monitor

1. Click **START NEW**.  
2. The tool will automatically send prompts, wait for generation, and download each image.  
3. Progress and previews are displayed live.
<img width="393" height="69" alt="image" src="https://github.com/user-attachments/assets/1bc409f4-b9dc-4894-b299-fce0e9dd9615" />

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
