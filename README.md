# 🏇 OurHub Racing API  
Real-time UK & Irish horse racing data for developers.  
Racecards • Runners • Jockey/Trainer Stats • AI Predictions

The **OurHub Racing API** provides clean, structured JSON data for UK & Irish race meetings.  
Powering the **Forma** racing predictor and developer tools, this API is ideal for:

- Racing apps  
- Prediction models  
- Betting analytics  
- Research dashboards  
- Odds comparison tools  
- Telegram/Discord bots  
- Data pipelines

➡ Official site: **https://racing.ourhub.site**  
➡ Get an API key: **https://racing.ourhub.site**

---

## 📡 Endpoints

### 🔹 1. Course Info  
**GET `/api/course-info/{race_date}`**  
Returns track, going, distance, class, prize & more.

### 🔹 2. Runner Info  
**GET `/api/runner-info/{race_date}`**  
All runners with jockey, trainer, weight, form & saddle numbers.

### 🔹 3. Performance Stats  
**GET `/api/performance-stats/{race_date}`**  
Jockey/trainer runs, wins, win-rates & performance metrics.

### 🔹 4. Predictions  
**GET `/api/predictions/{race_date}`**  
AI-powered ranked predictions with scoring & insights.

---

## 🧪 Example Request

```bash
curl -H "X-API-Key: YOUR_KEY" \
https://api.ourhub.site/api/course-info/2025-11-11

🔑 Authentication

Every request must include your API key:

X-API-Key: YOUR_KEY
You receive this instantly after subscribing on the website.

💳 Pricing (via Gumroad)
🟩 Starter – £5/mo

Course Info

Runner Info

1,000 requests/day

🟦 Professional – £10/mo

Starter features

Performance Stats

10,000 requests/day

🟥 Enterprise – £20/mo

Everything above

Predictions API

Unlimited requests

Priority support

Subscribe:
👉 https://racing.ourhub.site

📄 Example JSON Response

{
  "Wetherby": [
    {
      "race_time": "14:00",
      "race_name": "Handicap Hurdle",
      "distance": "2m",
      "age": "4yo+",
      "going": "Soft",
      "prize": "£10,000",
      "race_class": "Class 3"
    }
  ]
}


🧠 Use Cases

Machine learning models

AI racing predictors

Live widgets

Data scraping alternatives

Trading models

Historical tracking

Automated racing alerts

🏗 Built With

FastAPI

Python 3.10+

SQLite

Cloudflare protection

Forma Prediction Engine

📨 Support

For help, contact: racingapiaccess@papadev.xyz


⭐ Star This Repo

If you find the API useful, please consider starring the repo.
It helps others discover the project and supports my work.
