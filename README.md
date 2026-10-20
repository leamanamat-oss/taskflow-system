# TaskFlow: Student Task & Productivity Management System

**TaskFlow** is a responsive, web-based student task and productivity management system designed to help students organize, track, and manage their academic workloads effectively. Built as an offline-first hybrid web application, TaskFlow ensures seamless functionality even without an active internet connection while providing cloud database synchronization when online.

---

## 🌟 Key Features

* **Offline-First Storage:** Uses client-side **IndexedDB** for fast data persistence without relying strictly on a live server connection.
* **Cloud Backup & Syncing:** Integrated with **Firebase Firestore Database** to automatically backup and sync task data across devices.
* **File Attachments:** Handled efficiently using **Base64** file encoding for localized submission and database storage.
* **Responsive User Interface:** Tailored for both desktop browsers and mobile screen layouts.
* **Client-Side Authentication:** Secure and quick user access flow without complex back-end code overhead.

---

## 🛠️ Technology Stack

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla ES6+)
* **Local Storage:** IndexedDB (Browser Client Storage)
* **Cloud Database:** Firebase Firestore (Test Mode Active)
* **Deployment & Hosting:** GitHub Repositories & Vercel Hosting

---

## 🚀 Live Demo

You can access the live deployed web application here:
👉 **[TaskFlow System on Vercel](https://taskflow-system.vercel.app)** *(Replace with your actual Vercel link)*

---

## 📂 Project Structure

```text
taskflow-system/
│
├── index.html          # Main single-page application (UI, CSS, and JS Logic)
└── README.md           # Project documentation and details
