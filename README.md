# n8n Web Scraper & Article Summarizer

This workflow automates the process of finding and summarizing online content. It:

1. Searches the web for a topic using Google Custom Search.
2. Retrieves and processes the top articles.
3. Strips away unnecessary HTML and extracts clean text.
4. Condenses the content into 3–5 key bullet points with Google Gemini AI.
5. Stores the summary in Google Drive.

<img width="2046" height="867" alt="Screenshot from 2025-08-04 01-17-32" src="https://github.com/user-attachments/assets/edd82558-2c44-464a-8216-643a244a9151" />

The image above shows the complete n8n workflow with all connected nodes.
---

## 🚀 Features

* Automated search and retrieval of relevant articles
* HTML cleanup and text extraction
* Keyword-driven sentence selection
* Concise, AI-generated summaries
* Seamless Google Drive storage

---

## 🛠️ Requirements

* [n8n](https://n8n.io/) (local or cloud)
* Google Custom Search API key & CX ID
* Google Drive API credentials
* Google Gemini API key

---

## 📂 Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ankurghosh2910/n8n-web-scraper-summarizer.git
   ```
2. **Import the workflow** into n8n.
3. **Set up credentials** for:

   * Google Custom Search API (`GOOGLE_API_KEY`, `GOOGLE_CX_ID`)
   * Google Drive API
   * Google Gemini API key
4. **Activate** the workflow.

---

## ▶️ Usage

* Provide a topic as input.
* The workflow will:

  * Search Google for related articles.
  * Retrieve the top results.
  * Extract and clean the text.
  * Summarize the content.
  * Save it to Google Drive.

---

## 📜 License

Licensed under the MIT License.

---

## 🙌 Credits

* [n8n.io](https://n8n.io/)
* Google Custom Search API
* Google Gemini AI
