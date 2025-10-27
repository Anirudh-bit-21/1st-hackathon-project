# GLA Placement Prep Hub

This project is a comprehensive, AI-powered web application designed to help GLA University students prepare for job placements. It features a public landing page, a full user dashboard, and multiple tools driven by the Google Gemini AI to simulate interviews, generate coding problems, and provide company-specific preparation roadmaps.

## 🚀 How to Use

1.  Open the `index.html` file in your browser to see the main landing page.
2.  Click "Login" to navigate to the `auth.html` page.
3.  Use the following hard-coded credentials to log in:

    * **User ID:** `shahvez693@gmail.com`
    * **Password:** `Shahvez1213`

4.  After logging in, you will be redirected to the `main.html` dashboard, where you can access all the features.

## ⚠️ Important: AI Features Require an API Key

The core features of this application (AI Mock Interview, AI Roadmaps, AI Problem Generator, and the GLAI Assistant) **will not work** without a valid Google Gemini API key.

You must get your own API key from [Google AI Studio](https://aistudio.google.com/app/apikey) and paste it into the following files:

* `mock.html`
* `main.html`
* `codepractice.html`

In each file, find the JavaScript variable named `API_KEY` and replace the placeholder value with your own key.

```javascript
// Find this line in the <script> tag of mock.html, main.html, and codepractice.html
const API_KEY = "YOUR_API_KEY_GOES_HERE";
```

✨ Key Features
AI Mock Interview Arena (mock.html): Practice live interviews with a Gemini-powered AI. It validates company names, asks role-specific questions, and provides real-time feedback on your answers (clarity, accuracy, and structure).

AI Company Roadmaps (mock.html): Search for any company (e.g., Google, Microsoft) and get an AI-generated preparation roadmap, including key focus areas, top DSA questions, and recommended practice problems.

AI Coding Problem Generator (codepractice.html): Creates custom practice sets of LeetCode and HackerRank problems based on your chosen programming language (Python, Java, C++) and difficulty (Easy, Medium, Hard).

AI Assistant (main.html): A "GLAI Assistant" chatbot (also powered by Gemini) that can answer technical doubts and explain computer science concepts.

User Dashboard (main.html): A central hub to access all preparation tools and see a welcome message.

Profile Page (profile.html): A dedicated page to view user stats, activity summary, and personal information.

Modern UI: Fully responsive design built with Tailwind CSS, including a dark/light mode toggle.

📂 File Structure
index.html: The main public landing page.

auth.html: The login page with hard-coded user credentials.

main.html: The primary user dashboard after logging in. Features the "GLAI Assistant."

mock.html: The main application page. This is a single-page app (SPA) that contains the AI Interview Arena, Dashboard, and Company Roadmaps sections.

codepractice.html: The AI-powered coding practice generator page.

profile.html: The user's profile page, displaying activity and personal info.

test.html: An alternate/test version of the main dashboard.

🛠️ Technologies Used
Frontend: HTML5, Tailwind CSS

JavaScript (ES6+):

DOM Manipulation

fetch API for AI calls

localStorage for theme and user state

Web Speech API (SpeechRecognition) for live transcripts

AI: Google Gemini API

Libraries:

AOS (Animate on Scroll)

Typed.js

Lucide Icons# 1st-hackathon-project
# 1st-hackathon-project
# 1st-hackathon-project
