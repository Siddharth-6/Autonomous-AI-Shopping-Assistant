# 🛍️ Autonomous AI Shopping Assistant

An autonomous AI shopping assistant built using **MachinaOS** that can track products, compare prices across multiple shopping platforms, remember user preferences, and automatically send Telegram deal alerts using memory, scheduling, and live web scraping.

---

## 🚀 Features

* 🔍 Cross-platform product search
* 🧠 Persistent shopping memory
* 🤖 Autonomous deal monitoring
* 📲 Telegram integration
* 🌐 Live web scraping
* ⏰ Scheduled background execution
* 💰 AI-powered product comparison
* 📦 Product tracking & alerts
* ⭐ Intelligent recommendation engine
* 🛡️ Filtering of unreliable listings

---

## ⚙️ Workflow Architecture

```text
Telegram Receive
       ↓
    AI Agent
   ├── Memory
   ├── Web Scraper
   └── Scheduler
       ↓
Telegram Send
```

---

## 🧩 How It Works

1. Users interact with the assistant through Telegram.
2. The AI agent analyzes requests and recalls tracked products from memory.
3. The system dynamically generates shopping search URLs for stores like Amazon and Flipkart.
4. The web scraper extracts:

   * product name
   * price
   * rating
   * stock status
   * product link
5. The AI compares products across stores and filters unreliable listings.
6. The best recommendations and deal alerts are sent back through Telegram.
7. A scheduler periodically triggers autonomous deal scans in the background.

---

## 💬 Example Queries

```bash
watch gaming mouse under 1500

find best keyboard under 3000

compare Logitech M331 vs HP Z3700

check deals
```

---

## 🛠️ Tech Stack

* MachinaOS
* Gemini API
* Telegram Bot API
* Web Scraping
* AI Memory
* Cron Scheduler

---

## 🎯 Project Goal

The goal of this project is to explore **agentic AI workflows** where the model is not just generating text, but orchestrating memory, scheduling, live web interaction, and autonomous decision-making to behave like a persistent AI assistant.

---

## 📂 Repository Structure

```text
workflow/
prompts/
screenshots/
demo/
docs/
```

---

## 🔮 Future Improvements

* 📉 Price trend analytics
* 🧠 Smarter personalization
* 🛒 Auto-purchase approval flow
* 🧾 Warranty & subscription reminders
* 👥 Multi-user support
* 📊 Better ranking and recommendation logic

---

## 📸 Demo

https://github.com/user-attachments/assets/66e4e041-e264-4e79-94cc-a7aec94e2cd4
