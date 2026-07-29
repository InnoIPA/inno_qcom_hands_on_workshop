<h1 align="center"><span>🚀Hands-On Workshop🔥</span> Prep Site</h1>

<p align="center">
  <marquee direction="up" scrollamount="3" height="100px" style="background-color: #0d1117; border: 1px dashed #3b82f6; padding: 10px; border-radius: 6px; width: 100px; text-align: center;">
    <span style="font-size: 22px;">🚀</span><br>
    <span style="color: #ff4500; font-size: 16px;">🔥</span><br>
    <span style="color: #ff8c00;">*</span><br>
    <span style="color: #ffd700;">.</span><br>
    <span style="color: #555;">.</span>
  </marquee>
</p>

<p align="center">
  👉 <b>[<a href="https://innoipa.github.io/inno_qcom_hands_on_workshop/" style="color: #ff69b4; text-decoration: none;">Click Here to Access Web Platform</a>]</b> 👈
</p>

---

Welcome to the **Hands-On Workshop Prep Site**. This is a self-contained, browser-native platform for the **Qualcomm AI Hub × YOLO26 BYOM** workshop — it takes participants from pre-install, through hardware flashing, through the full day-of deployment script (FP32 → INT8 on the EXMP-Q911), to the on-site handouts.

**No repository cloning or code downloading is required for users.** Participants simply open this web platform in their browser to get everything ready before and during the live sessions. The whole site is bilingual (中文 / English, toggle in the header), supports dark/light theme, and has a global search (`⌘K` / `Ctrl+K`) that jumps straight to any step, tool, or troubleshooting tip.

---

## 🚀 Key Modules & Web Pages

<<<<<<< HEAD
### 1. [Overview](https://aiotads.github.io/iq-hands-on-workshop___confidential/index.html)
=======
This web platform is divided into 5 structured sections, fully optimized for technical training readiness:

### 1. [Overview](https://innoipa.github.io/inno_qcom_hands_on_workshop/)
>>>>>>> fa8fbb14e9d445786a4cd2f394bda4d167d3c729
The main landing page serves as the orientation center for the event.
* **Prerequisite Fast-Track:** Direct entry into the Pre-Install guide.
* **Interactive Agenda:** Full timeline of the workshop day, speaker-by-speaker.
* **Event Details:** Date, time, and venue for July 30, 2026.
<img width="1385" height="735" alt="overview_preview" src="https://github.com/user-attachments/assets/cb15d3c6-06a1-4013-bfce-b7c37c5265e3" />


<<<<<<< HEAD
### 2. [Pre-install Guide](https://aiotads.github.io/iq-hands-on-workshop___confidential/pre-install.html)
A Windows-focused environment preparation dashboard titled **"Get the Toolchain Ready."**
* **Quick Walkthrough Video:** A short video card at the top previews the whole pre-install flow before diving in.
* **Step-by-Step Instructions:** Interactive copy-to-clipboard code blocks for installing **Qualcomm Software Center (QSC)**, **PCAT Tool**, **QUD (Qualcomm USB Driver)**, and setting up **WSL2 + Ubuntu-22.04** — everything needed runs on a single Windows 11 host.
<img width="1337" height="846" alt="Pre_install" src="https://github.com/user-attachments/assets/7bf7df87-8693-423c-8641-124df63a6a0a" />


### 3. [Windows Flashing Guide](https://aiotads.github.io/iq-hands-on-workshop___confidential/flashing.html)
A highly visual, 8-step walkthrough for flashing the image onto the EXMP-Q911.
* **Qualcomm Toolchain Integration:** Prepare the board (EDL mode jumper), open xPCATApp, connect the Q911.
* **Hardware Interfacing:** Choose the image and UFS memory type, run the download, switch the jumper back to Normal mode, then boot into the system.
<img width="1328" height="842" alt="flashing_preview" src="https://github.com/user-attachments/assets/9a621529-e12b-401f-bcc6-06c901ab38f0" />


### 4. [Workshop Day Script](https://aiotads.github.io/iq-hands-on-workshop___confidential/script.html)
The core hands-on walkthrough: **Qualcomm AI Hub × YOLO26 — BYOM from FP32 to INT8, deployed on-device.** Steps 0 through 6, each with a copy-paste-ready script.
* **Offline-First, Online Optional:** Steps with an AI Hub/internet dependency (Step 4, 5.2, 5.5) have an independent offline/online toggle per step — offline is the recommended default so nothing depends on venue WiFi.
* **Watch Before You Run:** Every step links to its own short tutorial video (opens in a new tab).
* **Know It Worked:** Collapsible "success message" logs under every step show exactly what a good run looks like.
* **Stuck? Get Help Fast:** A troubleshooting shortcut at the bottom of each step opens one of two pop-up guides (Steps 1–5.2 & 5.5, or Steps 5.3–5.4) with a numbered recovery flow (`lsusb`, `exit`, `adb kill-server`, etc.).
* **See the Results:** Input/output image galleries for the on-device test step (5.4), opened in a lightbox.
* **Reference Tables:** Prerequisites and full package-folder layout are documented right on the page.


### 5. [Handouts](https://aiotads.github.io/iq-hands-on-workshop___confidential/handouts.html)
=======
### 2. [Pre-install Guide](https://innoipa.github.io/inno_qcom_hands_on_workshop/pre-install.html)
A robust environment preparation dashboard titled **"Get the Toolchain Ready."**
* **Everything at a Glance:** A consolidated status table tracking multi-platform dependencies across Windows and Ubuntu.
* **Step-by-Step Instructions:** Interactive copy-to-clipboard code blocks and download steps for essential tools including `adb`, Qualcomm Software Center, PCAT Tool, QUD, QDL, and Docker Desktop.
<img width="1337" height="846" alt="Pre_install" src="https://github.com/user-attachments/assets/7bf7df87-8693-423c-8641-124df63a6a0a" />


### 3. [Windows Flashing Guidel Guide](https://innoipa.github.io/inno_qcom_hands_on_workshop/flashing.html)
A highly visual, step-by-step walkthrough for deploying firmware/images onto the target device.
* **Qualcomm Toolchain Integration:** Clear guides on utilizing the Qualcomm Software Center, QPST/ePCAT apps, and QDL.
* **Hardware Interfacing:** Learn how to connect devices, choose memory types, execute the download option, and switch back to normal boot mode.
<img width="1328" height="842" alt="flashing_preview" src="https://github.com/user-attachments/assets/9a621529-e12b-401f-bcc6-06c901ab38f0" />


### 4. [Handouts](https://innoipa.github.io/inno_qcom_hands_on_workshop/handouts.html)
>>>>>>> fa8fbb14e9d445786a4cd2f394bda4d167d3c729
The on-site reference dashboard for physical and open-source materials.
* **Hardware Checklist:** What to bring yourself (a Windows 11 laptop) vs. what's provided on-site (EXMP-Q911, cables, monitor, UVC camera).
* **Qualcomm Account:** Reminder to register before arriving.
* **Resource Portals:** Redirection tiles to **iQ-Studio**, **iQ-Foundry**, the **Workshop Day Script** page, and the shared-folder download link for the workshop package.

---

## 🚦 How to Use This Site (For Participants)

As an attendee, you do **not** need to install Git, clone this project, or set up a local server. The platform runs completely on the client side.

1. **Access the Portal:** Open the deployment link provided by your workshop coordinators in any modern web browser.
2. **Prep at Home:** Work through **Pre-Install** to get QSC, PCAT, QUD, and WSL2 + Ubuntu-22.04 installed on your Windows laptop — no need to finish in one sitting.
3. **Flash Your Device:** Follow the **Flashing** guide's 8 steps when prompted by the instructor.
4. **Run the Workshop Script:** On the day, open **script.html** and run Steps 0–6 in order, offline mode by default. Watch a step's video first if you want a preview.
5. **Self-Troubleshoot:** If a step doesn't behave, use the amber "Having trouble?" shortcut under that step (or the sidebar troubleshooting buttons) — no separate FAQ page needed.

---

## 📄 License

This project is licensed under the MIT License - see the [MIT-LICENSE](MIT-LICENSE) file for details.
