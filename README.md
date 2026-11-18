<div align="center">

# ☁️ File Backup and Sync System

### A Secure, Self-Hosted Platform for File Backup, Synchronization and Recovery

<p>
  <img src="https://img.shields.io/badge/Project-Academic%20%7C%202026--27-blue?style=for-the-badge" alt="Academic Project">
  <img src="https://img.shields.io/badge/Backend-Django%20REST-green?style=for-the-badge" alt="Django REST">
  <img src="https://img.shields.io/badge/Frontend-React%20%2B%20Vite-61DAFB?style=for-the-badge" alt="React">
  <img src="https://img.shields.io/badge/Storage-MongoDB-47A248?style=for-the-badge" alt="MongoDB">
</p>

**Developed by**

| Student | Roll No. |
|:---:|:---:|
| **Nikhil Lanje** | 112 |
| **Rutik Harbale** | 125 |
| **Aditya Bandewar** | 155 |
| **Rushikesh Kadam** | 158 |

**Project Guide:** Ms. S. S. Panchal

Department of Computer Science and Engineering  
MGM's College of Engineering, Nanded  
B. Tech — CSE-A | Academic Year 2026–27

</div>

---

## 📌 About the Project

The **File Backup and Sync System** is a self-hosted platform designed to securely back up, synchronize, and manage files between a user's local computer and cloud storage.

The system combines a Python-based desktop synchronization agent, a Django REST API backend, and a React web dashboard. It monitors local file changes, detects updates using SHA-256 hashing, maintains file versions, handles synchronization conflicts, and protects stored files using encryption.

The project explores practical approaches to reliable file synchronization, data integrity, secure storage, and file recovery.

## ✨ Key Features

- **Automatic synchronization:** Monitors selected local folders and detects file changes.
- **Hash-based change detection:** Uses SHA-256 hashing to identify file modifications.
- **Version management:** Maintains file versions and supports version history.
- **Conflict handling:** Helps manage concurrent or conflicting file updates.
- **Secure storage:** Uses AES-256-GCM authenticated encryption for stored file data.
- **User authentication:** Provides JWT-based authentication.
- **File and folder management:** Supports organizing and managing cloud files.
- **Web dashboard:** Provides a React-based interface to access and manage files.
- **Backup and recovery:** Includes backup mechanisms to help protect and restore data.

## 🏗️ System Architecture

The project follows a client-server architecture with three main components:

| Component | Technology | Responsibility |
|---|---|---|
| Desktop Sync Agent | Python | Monitors local files and performs synchronization |
| Backend API | Django REST Framework | Authentication, file operations, synchronization and storage coordination |
| Web Dashboard | React + Vite | User interface for file and account management |
| Metadata Database | MongoDB | Stores application and file metadata |
| Local Sync Database | SQLite | Maintains desktop agent synchronization state |
| OTP Service | Python service | Supports email/SMS OTP workflows |

### Technology Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,django,react,vite,mongodb,sqlite,js,html,css,git,github" alt="Technology stack">
</p>

- **Programming:** Python, JavaScript
- **Backend:** Django, Django REST Framework
- **Frontend:** React, Vite, Axios
- **Database:** MongoDB, SQLite
- **Security:** AES-256-GCM, SHA-256, JWT, Argon2
- **Desktop monitoring:** Watchdog
- **Communication:** REST APIs

## 📂 Repository Structure

```text
.
├── Project Documents/
│   ├── Certifications/
│   │   └── Certification.pdf
│   ├── Copyright Proof/
│   │   └── Copyright proof Pdf.pdf
│   ├── Poster/
│   │   └── File Backup and sync Platform Poster.pdf
│   ├── Report & Plagiarism Report/
│   │   └── File Backup and Sync System Report.pdf
│   └── Research Paper & Submission Proof/
│       ├── CloudSyncVault_Research_Paper.pdf
│       └── Reserch Paper Submission Proof.pdf
│
└── Source Code/
    ├── app/                 # Python desktop synchronization agent
    ├── backend/             # Django REST API
    ├── frontend/            # React + Vite web dashboard
    ├── mail_otp_server/     # Email and SMS OTP service
    ├── requirements.txt
    └── README.md
```

## 📜 Project Documentation

All supporting project documents are available in the [`Project Documents`](Project%20Documents/) directory.

| Document | Description |
|---|---|
| [📘 Project Report](Project%20Documents/Report%20%26%20Plagiarism%20Report/File%20Backup%20and%20Sync%20System%20Report.pdf) | Detailed project report, design and implementation |
| [🎨 Project Poster](Project%20Documents/Poster/File%20Backup%20and%20sync%20Platform%20Poster.pdf) | Project overview and visual presentation |
| [🎓 Certification Details](Project%20Documents/Certifications/Certification.pdf) | Team members' completed certifications |
| [© Copyright Submission Proof](Project%20Documents/Copyright%20Proof/Copyright%20proof%20Pdf.pdf) | Copyright application and payment submission evidence |
| [📄 Research Paper](Project%20Documents/Research%20Paper%20%26%20Submission%20Proof/CloudSyncVault_Research_Paper.pdf) | Research paper: *CloudSyncVault* |
| [📩 Research Paper Submission Proof](Project%20Documents/Research%20Paper%20%26%20Submission%20Proof/Reserch%20Paper%20Submission%20Proof.pdf) | Journal submission confirmation and manuscript details |

## 🎓 Team Certifications

The team completed certifications in cloud computing, full-stack development, Django, MongoDB, and software engineering.

| Student | Certifications |
|---|---|
| **Nikhil Lanje** | Cloud Computing Using AWS; MongoDB; Software Engineering and Agile Software Development |
| **Rutik Harbale** | Cloud Computing Using AWS; Django Certification Course; MongoDB |
| **Aditya Bandewar** | Cloud Computing (NPTEL – Elite); Full Stack Web Development; Django Certification Course; MongoDB |
| **Rushikesh Kadam** | Cloud Computing Using AWS; MongoDB |

The consolidated certificate information is available in [Certification.pdf](Project%20Documents/Certifications/Certification.pdf).

## © Copyright Application

A copyright application has been submitted to the **Copyright Office, Government of India**, for the project work.

| Particular | Details |
|---|---|
| Work title | File Backup and Sync Platform |
| Application form | Form XIV |
| Class of work | Artistic Work |
| Diary Number | AT-53740/2026-CO |
| Filing date | 18 November 2026 |
| Receipt number | 283475 |
| Applicant | Nikhil Padmakar Lanje |

**Note:** The linked document is proof of application submission and fee payment. It should not be interpreted as a copyright registration certificate or a statement that registration has been granted.

[View Copyright Application Submission Proof](Project%20Documents/Copyright%20Proof/Copyright%20proof%20Pdf.pdf)

## 📑 Research Paper

The project research work is documented in the paper:

**CloudSyncVault: A Prototype Self-Hosted File Backup and Synchronization System with Encrypted Storage and Version-Aware Updates**

**Authors:** Nikhil Lanje, Rushikesh Kadam, Aditya Bandewar, Rutik Harbale and Sonali Panchal.

| Particular | Details |
|---|---|
| Journal | IEEE Transactions on Cloud Computing |
| Manuscript ID | TCC-2026-11-1077 |
| Submission date | 16 November 2026 |
| Manuscript type | Regular Paper |
| Submission version | Initial Submission |
| Status in supplied confirmation | Successfully submitted online; under consideration |

The paper describes the system architecture, implementation, encryption approach, version-aware synchronization, and functional validation.

**Publication status:** Submission does not mean acceptance or publication. The manuscript status should be checked through the journal's official submission system.

- [Read the Research Paper](Project%20Documents/Research%20Paper%20%26%20Submission%20Proof/CloudSyncVault_Research_Paper.pdf)
- [View Submission Proof](Project%20Documents/Research%20Paper%20%26%20Submission%20Proof/Reserch%20Paper%20Submission%20Proof.pdf)

## 💻 Source Code

The complete implementation is available in the [`Source Code`](Source%20Code/) directory.

| Directory | Description |
|---|---|
| [`app/`](Source%20Code/app/) | Desktop synchronization agent |
| [`backend/`](Source%20Code/backend/) | Django REST API and storage services |
| [`frontend/`](Source%20Code/frontend/) | React web dashboard |
| [`mail_otp_server/`](Source%20Code/mail_otp_server/) | Email and SMS OTP service |

### Running the Project

The following is a high-level local setup guide. Configure each component using its own `.env.example` file and its README before starting it.

**1. Clone the repository**

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
```

**2. Backend setup**

```bash
cd "Source Code/backend"
python -m venv venv
```

Activate the environment:

```bash
# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate
```

Install dependencies and configure environment variables:

```bash
pip install -r requirements.txt
```

Copy `.env.example` to `.env`, configure the required values, and start Django:

```bash
python manage.py runserver 8000
```

**3. Frontend setup**

Open another terminal:

```bash
cd "Source Code/frontend"
npm install
npm run dev
```

**4. Desktop agent setup**

Open another terminal:

```bash
cd "Source Code/app"
pip install -r requirements.txt
```

Configure the required backend connection and authentication settings before running the desktop agent. Refer to the source code documentation for the appropriate launch command.

**Important:** Do not commit `.env` files, passwords, API keys, database credentials, JWT secrets, or encryption keys to GitHub. Use the supplied `.env.example` files as configuration templates.

## 👥 Project Team

| Name | Roll No. | Role |
|---|---:|---|
| Nikhil Lanje | 112 | Project Team Member |
| Rutik Harbale | 125 | Project Team Member |
| Aditya Bandewar | 155 | Project Team Member |
| Rushikesh Kadam | 158 | Project Team Member |

**Project Guide:** Ms. S. S. Panchal  
**Department:** Computer Science and Engineering  
**Institute:** MGM's College of Engineering, Nanded  
**University:** Dr. Babasaheb Ambedkar Technological University, Lonere

## 🙏 Acknowledgement

We express our sincere gratitude to our project guide, **Ms. S. S. Panchal**, for her valuable guidance, encouragement, and continuous support throughout the development of this project.

We also thank the Department of Computer Science and Engineering and MGM's College of Engineering, Nanded, for providing the resources and academic support required to complete this work.

## 📌 Project Information

- **Project:** File Backup and Sync System
- **Research Paper Name:** CloudSyncVault
- **Degree:** Bachelor of Technology
- **Branch:** Computer Science and Engineering
- **Academic Year:** 2026–27
- **Class:** B. Tech CSE-A

---

<div align="center">

**Built with dedication by the File Backup and Sync System team.**

⭐ If you find this project interesting, consider giving the repository a star!

</div>
