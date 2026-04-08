# 🚀 EasyBacklink — AI-Powered SEO Prompt Generator

![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)
![Built With](https://img.shields.io/badge/built_with-AI%20%7C%20SEO%20Tools-orange)

EasyBacklink is a lightweight, browser-based tool designed to streamline SEO workflows by generating AI-powered prompts from keyword datasets. It enables content creators, SEO specialists, and marketers to quickly produce structured prompts and content using spreadsheet-driven inputs.

---

## ✨ Features

* 📂 Upload `.xlsx` keyword files
* 🔍 Select and manage keywords dynamically
* 🌐 Automatic URL mapping (target page detection)
* 🧠 AI-powered prompt generation
* ✏️ Rich text editor for output customization
* 📜 Prompt templates for different SEO use cases
* 💾 Local storage for API key (privacy-first)
* 🕘 Upload history tracking
* ⚡ Fast, fully client-side execution

---

## 🧩 How It Works

1. Upload an Excel file containing keywords
2. Select a keyword from the dataset
3. Tool assigns or suggests a relevant target URL
4. Choose a prompt type (e.g., backlink, article, outreach)
5. Generate prompt using AI
6. Edit and refine output in the built-in editor

---

## 📁 Input Format

Your `.xlsx` file should follow a simple structure:

| Keyword        | URL (optional)        |
| -------------- | --------------------- |
| best seo tools | https://example.com   |
| backlink tips  | https://example.com/b |

* **Keyword** → required
* **URL** → optional (auto-handled if missing)

---

## 🧠 AI Integration

This tool supports AI generation via:

* Google Gemini API (user-provided key)

### 🔐 API Key Handling

* Stored **only in your browser**
* Uses `localStorage`
* Never sent to any backend server

---

## 🖥️ Tech Stack (Observed / Likely)

| Layer    | Technology           |
| -------- | -------------------- |
| Frontend | HTML / CSS / JS      |
| AI API   | Gemini API           |
| Storage  | Browser localStorage |
| Hosting  | Netlify              |

> Note: Exact stack may vary if backend or frameworks are added.

---

## 🚀 Getting Started

### Option 1 — Use Online

👉 https://easybacklink.netlify.app/

No installation required.

---

### Option 2 — Run Locally (Recommended Setup)

```bash
git clone https://github.com/your-username/easybacklink.git
cd easybacklink
npm install
npm run dev
```

> Adjust commands based on your actual stack (Vite, Next.js, etc.)

---

## 📦 Suggested Project Structure

```
easybacklink/
├── public/
├── src/
│   ├── components/
│   ├── utils/
│   ├── services/
│   └── main.js
├── package.json
└── README.md
```

---

## 🧪 Use Cases

* SEO backlink outreach generation
* Blog content ideation
* Keyword-based article drafts
* Content scaling workflows
* Agency automation pipelines

---

## ⚠️ Limitations

* Requires manual API key input
* No backend persistence
* Limited validation for Excel formats
* AI output quality depends on prompt structure

---

## 🔮 Future Improvements

* Multi-file support
* Keyword clustering
* Built-in SERP analysis
* Export to CSV / Docs
* Team collaboration features
* Backend integration (optional)

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Submit a pull request

---

## 📄 License

MIT License — feel free to use and modify.

---

## 💡 Author Notes

This tool is designed for speed and simplicity — ideal for rapid SEO workflows without heavy infrastructure.

---

## ⭐ Support

If you find this useful:

* Star the repo ⭐
* Share with others
* Suggest improvements

---
