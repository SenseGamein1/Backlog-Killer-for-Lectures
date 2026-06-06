# ⚔️ Backlog Killer

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

**Backlog Killer** is a powerful, gamified tracking dashboard built to help students and professionals systematically eradicate their pending tasks, lectures, and assignments. Operating entirely within the browser as a single file, it requires no backend servers or complex setups.

## 🎯 Motivation: Why This Exists

Traditional to-do lists fail when it comes to academic or intense professional backlogs. When you are behind on 20 lectures and 15 assignments, you don't just need a checklist—you need a **strategy**. 

I built this program to solve the anxiety of falling behind. Instead of staring at an overwhelming pile of work, Backlog Killer calculates exactly how many hours of study you need and gives you a concrete **Clearance Target Date** based on your weekly pacing (e.g., 14, 21, 28, or 35 hours per week). It turns an impossible mountain of stress into a manageable, gamified timeline.

## ✨ Features

* **📊 Global Diagnostics Matrix**: Calculates your total syllabus clearance percentage and dynamically estimates your target clearance date based on your selected pacing.
* **⚡ Quick Subjects Hub**: Gamified stepper components with threat-level visual indicators (Clean, Warn, Critical) to manage your Lectures (LEC), Daily Practice Problems (DPP), and Homework (HW).
* **☁️ Cloud Sync Engine**: Seamlessly sync your progress across your phone and PC using a free JSONBin.io API integration. 
* **💾 Local String Backup**: Export and import your entire state matrix as a Base64 encoded string for offline backups.
* **↩️ History Engine**: Full Undo/Redo capabilities so you never accidentally lose your logging data.
* **📝 Daily Live Queue**: Track micro-tasks day-by-day and commit historical logs of your study performance.

## 🚀 Getting Started

### Prerequisites
Absolutely none. If you have a web browser (Chrome, Edge, Safari, Firefox), you can run this app.

### Installation & Usage
[🌐 Launch App in Browser Here](https://sensegamein1.github.io/Backlog-Killer-for-Lectures/BacklogKiller.html)
Bookmark the page for daily use!

[📥 Download & Install Here](https://github.com/SenseGamein1/Backlog-Killer-for-Lectures/archive/refs/heads/main.zip)
**Instructions:**
1. Click the link above to download the `.zip` file to your PC.
2. Extract the folder.
3. Double-click `BacklogKiller.html` to run the app directly in your browser!

**Generalizing the App**: By default, it is populated with Physics, Math, and Chemistry. You can use the UI to **Drop** these subjects and add your own via the Advanced Settings menu (e.g., "Web Development", "Marketing", "Language Learning").

### Setting up Cloud Sync (Optional)
To use this on both your phone and laptop:
1. Create a free account at [JSONBin.io](https://jsonbin.io/).
2. Create a new empty bin and generate a Master API Key.
3. Paste the **Bin ID** and **API Key** into the Cloud Sync Engine section in the app.
4. Hit **Push** on your main device, and **Pull** on your secondary device!

## 🤖 Extend and Modify with AI

This entire project is cleverly contained within a single HTML file. You don't need to be an expert programmer to update it! 

To add new features or change the styling:
1. Open ChatGPT, Claude, or Gemini.
2. Paste the entire `BacklogKiller.html` code into the chat.
3. Give a prompt like: *"I want to change the theme from Purple to Neon Green. Update the CSS for me."* OR *"Add a new tracker next to HW called 'Mock Tests'."*
4. Copy the newly generated code, paste it back into your file(could be firstly txt which you can change into html after pasting), and save.

## 📄 License
This project is open-source and available under the MIT License.
