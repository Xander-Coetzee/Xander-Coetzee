# Interactive Portfolio - Xander Coetzee

A modern, interactive digital portfolio showcasing the skills, projects, and professional journey of Xander Coetzee, a BSc Hons Computer Science graduate specializing in Cyber Security, Digital Forensics, and AI.

## 🚀 Overview

This project is a single-page responsive web application designed to serve as a dynamic CV and portfolio. It features a clean, "Warm Minimalist Tech" aesthetic and integrates an AI-powered chat assistant to answer questions about Xander's background.

## ✨ Features

- **AI Digital Twin**: An integrated chat widget powered by Google's Gemini API that acts as a virtual assistant, answering questions based on Xander's resume context.
- **Dynamic Project Showcase**: A filterable grid of projects categorized by domain (Security, AI/ML, Data/Dev).
- **PDF Generation**: Built-in functionality to generate and download a PDF version of the portfolio using `html2pdf.js`.
- **Responsive Design**: Fully responsive layout optimized for desktop, tablet, and mobile devices using Tailwind CSS.
- **Interactive UI**: Smooth scrolling, fade-in animations, and glassmorphism effects for a premium user experience.

## 🛠️ Technologies Used

- **HTML5**: Semantic structure.
- **Tailwind CSS**: Utility-first CSS framework for styling and responsiveness.
- **JavaScript (Vanilla)**: Core logic for interactivity, API integration, and DOM manipulation.
- **Google Gemini API**: Powers the AI chat assistant.
- **FontAwesome**: Iconography.
- **Marked.js**: Markdown parsing for AI chat responses.
- **html2pdf.js**: Client-side PDF generation.

## ⚙️ Setup & Usage

Since this is a static HTML file, it can be run directly in any modern web browser. However, for the AI features to work, you need to configure an API key.

1.  **Clone or Download**:

    ```bash
    git clone https://github.com/Xander-Coetzee/Interactive_Portfolio.git
    # OR download the ZIP file
    ```

2.  **Configure API Key**:

    - Open `Interactive_Portfolio.html` in a text editor.
    - Locate the `apiKey` variable in the script section at the bottom of the file (around line 750).
    - Insert your Google Gemini API key:
      `javascript
const apiKey = "YOUR_GEMINI_API_KEY_HERE";
`
      > **Note**: You can get a free API key from [Google AI Studio](https://aistudio.google.com/).

3.  **Run**:
    - Simply double-click `Interactive_Portfolio.html` to open it in your browser.
    - **Tip**: For the best experience (and to avoid some local file CORS issues with certain features), it's recommended to serve the file using a local development server (e.g., Live Server in VS Code or `python -m http.server`).

## 📂 Project Structure

The entire application is contained within a single file for portability and simplicity:

- `Interactive_Portfolio.html`: Contains all HTML, CSS (via Tailwind CDN), and JavaScript logic.

## 📄 License

This project is open for viewing and educational purposes. Content and personal details remain the property of Xander Coetzee.

<!-- Triggering deployment for API key update -->
