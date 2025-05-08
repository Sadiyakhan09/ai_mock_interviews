🎤 InterviewGenie: AI Mock Interviews

**InterviewGenie** is a modern job interview preparation platform powered by **Vapi AI Voice agents**, built with **Next.js**, **Tailwind CSS**, **Firebase**, and more. This project is designed to help users simulate real interviews, receive instant AI feedback, and improve their performance — all inside a sleek, modern interface.

## 📋 Table of Contents
- [🤖 Introduction](#-introduction)  
- [⚙️ Tech Stack](#-tech-stack)  
- [🔋 Features](#-features)  
- [🤸 Quick Start](#-quick-start)  
- [🕸️ Snippets](#-snippets)  
- [🔗 Assets](#-assets)  
- [🚀 More](#-more)  


## 🤖 Introduction
Built with **Next.js** for both frontend and backend logic, **Firebase** for authentication and data management, and styled using **Tailwind CSS**, **InterviewGenie** integrates **Vapi AI voice agents** and **Google Gemini** to deliver an immersive AI-driven interview experience.

Whether you're a developer looking to improve your interview readiness or a learner wanting to explore modern full-stack development, this project is the perfect playground.

If you need help or run into issues, join our **Discord community (50k+ members)** — a vibrant place to connect and get support.

## ⚙️ Tech Stack
- **Next.js**
- **Firebase**
- **Tailwind CSS**
- **Vapi AI**
- **shadcn/ui**
- **Google Gemini API**
- **Zod**


## 🔋 Features
✅ Authentication with Firebase (Sign Up / Sign In)  
✅ Create AI-powered interviews using Vapi + Gemini  
✅ Take mock interviews and receive instant AI feedback  
✅ Modern UI/UX using Tailwind CSS + shadcn/ui  
✅ Dashboard to manage interview history  
✅ Detailed interview transcripts and insights  
✅ Fully responsive design  
✅ Clean, scalable code architecture


## 🤸 Quick Start
### Prerequisites
Make sure you have the following installed:
- **Git**  
- **Node.js**  
- **npm**

### Clone the Repository
```bash
git clone https://github.com/Sadiyakhan09/ai_mock_interviews.git
cd ai_mock_interviews
````

### Install Dependencies
```bash
npm install
```

### Set Up Environment Variables
Create a `.env.local` file in the root folder and add:

NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

Replace with your actual **Firebase** and **Vapi** credentials.
### Run the Project
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.
---

## 🕸️ Snippets
* **globals.css** → Global styles
* **lib/utils.ts** → Utility functions
* **/app/api/vapi/generate/route.tsx** → Generate questions prompt
* **lib/actions/general.action.ts** → Generate feedback prompt
* **app/(root)/interview/\[id]/feedback/page.tsx** → Display feedback
* **Dummy Interviews** → Sample interview data

---

## ✨ Acknowledgements
* [Vapi AI](https://vapi.ai)
* [Firebase](https://firebase.google.com)
* [shadcn/ui](https://ui.shadcn.com)


⭐ If you like this project, **give it a star on GitHub!**
