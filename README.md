# AI Expense Tracker: Intelligent Expense Management System

AI Expense Tracker is an automation built with `Make` that fully handles personal or business expense tracking.

Users can simply take a photo of a printed receipt, send a PDF file, or type a text message. The system automatically recognizes the content, classifies the expense, and logs the data in real-time, providing an instant confirmation report to the user via a Telegram bot.

---

## 📸 How It Works

1.  **Submission:** The user sends a receipt (photo, PDF, or text) to the Telegram bot.
2.  **Data Recognition:** An AI-powered OCR module extracts text and numbers from the document.
3.  **Semantic Classification:** The system analyzes the text's context (e.g., store name, items purchased) and automatically assigns a relevant category, such as "Groceries," "Utilities," "Transport," or "Goods."
4.  **Data Storage:** All structured data is saved to a Google Sheet or Airtable base with the following fields:
    -   Purchase Date
    -   Store Name
    -   Category
    -   Amount & Currency (UAH / USD / EUR)
    -   Comment/Description
5.  **Instant Feedback:** The user immediately receives a confirmation message in the bot, summarizing the processed data.

---

## 🧩 Tech Architecture

-   **Automation Platform:** `Make`
-   **AI & OCR:** `Google Cloud Vision (OCR)`, `OpenAI (GPT for classification)`
-   **Database:** `Google Sheets` / `Airtable`
-   **User Interface:** `Telegram Bot API`

---

## 💼 Business Impact

✅ **Fully automated expense tracking** without any manual data entry.
✅ **Instant feedback loop** for the user after each submission.
✅ **Reduces time spent on financial administration** to mere seconds per receipt.
✅ **Supports multi-currency tracking** (UAH, USD, EUR), making it suitable for travel and international business.
✅ **Creates a structured data foundation** ready for advanced AI-powered analytics, such as generating charts, statistics, and spending forecasts.
