# 📖 Mini-Course

The following Religious Mini-Course was created for **Ms. Peggy**.

---

## 🌿 Minimalist HTML LMS Template

A fully in-house, self-contained **Learning Management System (LMS)** template designed for a mini-course or microlearning projects.  
This system is built for simplicity — **no external CMS or complex setup required.**  
Just open `index.html` to start.

---

## ✨ Features

### 🏠 Home + 4 Lesson Pages
Each lesson includes:

- Embedded **YouTube videos**
- Embedded **Wayward Interactive Video Quizzes**
- Built-in **interactive elements** (matching, drag & drop, self-grading quizzes)
- Seamless navigation between lessons

### 💬 Discussion Plug-in
HTML5 discussion area integrated at the bottom of each lesson for learner comments or journaling.

### 📎 Floating Submit Assignment Button
Always visible on screen for easy access.  
Clicking it opens a preview and upload form (supports images or PDFs).

### 🖼 Customizable Image Placeholders
Replace course thumbnails or in-lesson images easily by uploading your own.

### 📄 Standalone, Copy-and-Edit Structure
Simply copy the project folder, replace the text, videos, and images — your course is ready.

---

## 🧭 How to Use

### 1. Open the Template
- Download or clone this folder.  
- Open `index.html` in your browser to preview the LMS.

### 2. Replace Lesson Content
**To update:**

- Replace the `<h2>` title and any paragraph text.  
- Swap the YouTube video link (only change the video ID after `/embed/`).  
- Swap **Wayground link** after creating your interactive video:  
  [How to Create an Interactive Video on Wayground](https://support.wayground.com/hc/en-us/articles/29753577747225-Create-an-Interactive-Video)  
- Add or edit your simple interaction text as needed.

### 3. Customize the Images

You can **replace them by keeping the same file names** or **change the filenames in HTML**.

🖼 **Recommended format:** `.jpg` or `.png`  
📏 **Size:** Already predetermined in HTML (corner image next to title of lesson)

### 4. Interactive Features

#### 🧩 Matching / Drag & Drop
Pre-coded mini-activities inside each lesson using pure HTML5 + JavaScript.  
Update the question text or options inside the variable blocks.

#### ✅ Self-Grading Quiz
Each quiz includes automatic feedback and score display.  
To customize, edit your quiz data within the JavaScript file.

### 5. Discussion Plug-in
You can:

- Replace it with your own discussion plug-in embed code  
- Or use the default HTML5 local storage version for offline journaling

### 6. Floating “Submit Assignment” Button
This button is fixed to the lower right of the screen:

```html
<button id="submitBtn">📎 Submit Assignment</button>

📎 Floating Submit Assignment Button
Always visible on screen for easy access.
Clicking it opens a preview and upload form (supports images or PDFs).


When clicked, a small pop-up appears where users can:

Upload an image or document

Preview before submitting


To customize the destination:
Edit submit.js → update the form action (Replace Formspree address/custom endpoint).

📄 Standalone, Copy-and-Edit Structure
Simply copy the project folder, replace the text, videos, and images — your course is ready.



📢 Credits

Created by @edtechjessy


