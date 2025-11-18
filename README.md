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
➡ Get an API key: **https://ourhub.gumroad.com**

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
