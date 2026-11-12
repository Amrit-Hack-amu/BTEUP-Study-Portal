# 🎓 BTEUP Study Portal

[![Live Demo](https://img.shields.io/badge/Live_Portal-Visit_Site-38bdf8?style=for-the-badge&logo=githubpages&logoColor=white)](https://amrit-hack-amu.github.io/BTEUP-Study-Portal/)
[![Repo Size](https://img.shields.io/github/repo-size/Amrit-Hack-amu/BTEUP-Study-Portal?style=for-the-badge&color=818cf8)](https://github.com/Amrit-Hack-amu/BTEUP-Study-Portal)
[![Total Views](https://hits.sh/amrit-hack-amu.github.io/BTEUP-Study-Portal.svg?view=today-total&style=for-the-badge&label=Views&color=34d399&labelColor=1e293b)](https://amrit-hack-amu.github.io/BTEUP-Study-Portal/)

A fast, responsive, and interactive static web portal built for **BTEUP (Board of Technical Education, Uttar Pradesh)** diploma students to access unit-wise theory notes, bilingual PDFs (English & Hinglish), and lab practical files directly in the browser.

---

## ✨ Key Features

- **Multi-Dimensional Filtering:** Filter study materials instantly by **Branch** (CSE, IT, ME, CE, EE, EC), **Semester** (1st to 6th), **Subject**, or real-time keyword search.
- **In-Browser Document Viewer:** Read HTML notes and PDF documents inside a built-in full-screen modal viewer without forced downloads or external redirects.
- **Client-Side Admin Dashboard:**
  - Secured via SHA-256 hash authentication.
  - Toggle visibility (`ON`/`OFF`) of individual units or resources on the fly.
  - Edit existing note metadata (branch, semester, subject, tags, descriptions) or add new files.
  - One-click JSON configuration export for permanent updates via Git.
- **Custom Preloader & UI:** Dark-mode glassmorphic interface with a custom morphing dots-to-logo startup animation and live visitor tracking.

---

## 📚 Currently Available Content (5th Semester CSE)

### 1. Information Security (IS)
- **Interactive HTML Notes:** Units 1 to 5 + Complete Lab Practical File (`practical.html`)
- **English PDFs:** `IS_Unit1_Notes_English.pdf` – `IS_Unit5_Notes_English.pdf`
- **Hinglish PDFs:** `IS_Unit1_Notes_Hinglish.pdf` – `IS_Unit5_Notes_Hinglish.pdf`

### 2. Mobile Application Development (MAD)
- **Interactive HTML Notes:** Unit 1 (`Android_Unit_1_BTEUP_CSE.html`)
- **English & Hinglish PDFs:** Units 1 to 3 (`MAD_Unit1` – `MAD_Unit3`)

---

## 📂 Project Structure

```text
BTEUP-Study-Portal/
├── index.html                        # Main landing page, filters, viewer & admin dashboard
├── logo.png                          # Custom portal favicon & preloader logo
├── unit1.html - unit5.html           # Information Security theory notes
├── practical.html                    # Information Security lab practical file
├── Android_Unit_1_BTEUP_CSE.html     # MAD Unit 1 interactive notes
├── IS_Unit*_Notes_*.pdf              # Information Security English & Hinglish PDFs
├── MAD_Unit*_Notes_*.pdf             # Mobile Application Development PDFs
└── README.md                         # Project documentation
```

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Custom Properties, CSS Grid/Flexbox, Keyframe Animations), Vanilla JavaScript (ES6+)
- **Security:** Web Crypto API (`SHA-256` client-side credential verification)
- **Hosting & Analytics:** GitHub Pages & `hits.sh` SVG Badge Counter

---

## 🚀 Updating & Managing Content

1. Open the live portal and click **⚙ Portal Admin** in the top-right corner.
2. Authenticate using your admin key to toggle visibility, edit categories, or register newly uploaded files.
3. Click **📋 Copy Config for VS Code**, replace the `DEFAULT_DATA` array inside `index.html`, place the corresponding `.html` or `.pdf` files in the root folder, and push to `main`:
   git add .
   git commit -m "Update study materials"
   git push origin main

---

## 👨‍💻 Author

### Amrit Kumar Singh

[![GitHub](https://img.shields.io/badge/GitHub-@Amrit--Hack--amu-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Amrit-Hack-amu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amrit_Kumar_Singh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amrit-kumar-singh-)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Amrit-Hack-amu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amrit-kumar-singh-)