# 🍚 WalmartGenie – Your AI Shopping Companion

[![Demo Video](https://img.youtube.com/vi/TFmY_R624Ew/0.jpg)](https://www.youtube.com/watch?v=TFmY_R624Ew)

WalmartGenie is an **AI-powered shopping assistant** that helps users instantly discover **hidden gems**, trending picks, best deals, and virtually try on fashion items — all in seconds.

Built for the **Walmart Sparkathon 2025**, WalmartGenie transforms the Walmart shopping experience with smart recommendations, real-time product discovery, and a modern shopping UI.

---

## 🚨 The Problem

Millions of high-quality Walmart products go undiscovered due to poor visibility:

* 🛍️ 50% of users don’t browse past page 2
* 📉 60% of great products go unsold
* 💔 35% of online sellers fail within 120 days
* 💸 Discovery issues cost retailers **>\$369B/year**

---

## 💡 Our Solution: WalmartGenie

A blazing-fast AI shopping assistant that understands natural language queries like:

> “Running shoes under \$100 for flat feet”

It delivers laser-targeted suggestions powered by OpenAI and Walmart product data.

---

### 🔍 Key Features

| Feature               | Description                                                    |
| --------------------- | -------------------------------------------------------------- |
| 💎 Hidden Gems        | High-rated, low-visibility items (core innovation)             |
| 📈 Trending Picks     | Products gaining traction based on real-time shopping trends   |
| 💰 Value Deals        | Top 8 items with the steepest discounts                        |
| 👗 Virtual Try-On     | AR previews for clothing using Gemini Vision + Expo            |
| 🤖 Smart Alternatives | AI-suggested product swaps in the same price range or category |

---

## ⚙️ Tech Stack

* **Frontend**: React Native + Gifted Chat UI
* **Backend**: Node.js, Express.js, MongoDB, Firebase
* **AI/NLP**: OpenAI GPT API, Google Gemini API
* **AR Try-On**: Expo + Google Gemini Vision
* **Data Layer**: Firebase + Walmart product JSON
* **Styling**: NativeWind (Tailwind for React Native)
* **Navigation**: React Navigation

---

## 📊 Impact (Projected)

| Metric              | Result                     |
| ------------------- | -------------------------- |
| 🛍️ Conversion Lift | +23% (Glassix, 2024)       |
| 🔁 Repeat Visits    | +61% (Forrester, 2023)     |
| ⏱️ Purchase Speed   | 30% faster decision-making |

WalmartGenie replaces slow browsing with instant, intelligent discovery.

---

## 📆 Project Structure

```
drippy/
├── components/
│   └── WalmartChatbot.tsx          # AI chatbot component
├── screens/
│   ├── HaulScreen.tsx              # Main shopping screen
│   ├── ProductDetailScreen.tsx     # Product details
│   ├── TryingRoomScreen.tsx        # AR try-on experience
│   └── WardrobeScreen.tsx          # Saved/personalized items
├── utils/
│   ├── walmartDataSource.ts        # Handles Walmart product data
│   └── dataSource.ts               # Legacy data support
├── navigation/
│   └── index.tsx                   # App routing
└── assets/
    └── dataset/
        └── walmart-products.csv    # Product data file
```

---

## ⚙️ Setup Instructions

### 1. Install Dependencies

```bash
npm install
```

---

### 2. Environment Configuration

Create a `.env` file in the root directory:

```env
FIREBASE_API_KEY=
OPENAI_API_KEY=
GOOGLE_CLOUD_API_KEY=
```

#### 🔑 How to Get API Keys

* **Gemini (Google AI) API Key**

  1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
  2. Click **"Get API Key"**
  3. Paste it into `GOOGLE_CLOUD_API_KEY`

* **OpenAI API Key**

  1. Go to [OpenAI API Dashboard](https://platform.openai.com/account/api-keys)
  2. Click **"Create new secret key"**
  3. Paste it into `OPENAI_API_KEY`

* **Firebase API Key**

  1. Go to [Firebase Console](https://console.firebase.google.com/)
  2. Create/select a project → Project Settings → General
  3. Under **"Your apps"**, find your `apiKey`
  4. Paste into `FIREBASE_API_KEY`

> ⚠️ **Don’t forget:** Enable Firestore and configure basic security rules!

---

### 3. Run the Application

Start the development server:

```bash
npm start
```

Then press:

* `a` → Launch on Android
* `i` → Launch on iOS (macOS only)
* `w` → Open in Web browser

> 📱 **Tip:** Use [Expo Go](https://expo.dev/client) on your phone to scan the QR code and preview instantly.

---

## 🌟 Unique Selling Points

* **Real-time Shopping Assistant**: Get instant product suggestions via AI
* **AR Try-On**: Try clothes virtually before buying
* **Smart Discovery**: No more endless scrolling — get to the best picks fast
* **Integrated Chatbot UI**: Floating, interactive assistant powered by Gemini

---

## 📩 Features Summary

### 🛍️ Shopping Experience

* Full integration with Walmart product data
* Modern UI with intuitive categories and filters
* Featured collections and trending sections
* Rich product detail pages with options

### 🤖 AI Chatbot Assistant

* Gemini AI–powered smart chat
* Understands product, budget, occasion-based queries
* Offers product cards with direct interactions
* Floating assistant UI with real-time suggestions

### 👗 Virtual Try-On

* Real-time AR fitting room for fashion items
* Personalized try-before-you-buy experience

---

## 👥 Contributors

| Name            
| --------------- 
| Jatin Narayan   
| Shreyansh Gupta 
| Shashank Panday 
| Satyendra Singh 

---

## 🏁 Built for Walmart Sparkathon 2025

This project was submitted to the **Walmart Sparkathon 2025**, a challenge to reimagine how Walmart customers discover and shop smarter.

---

## 🎥 Watch the Demo

Click below to watch the full walkthrough:

[![Demo Video](https://img.youtube.com/vi/TFmY_R624Ew/0.jpg)](https://www.youtube.com/watch?v=TFmY_R624Ew)

---

## 🤝 Contributing

We welcome contributions from developers, designers, and data enthusiasts!

### Steps to Contribute:

1. Fork the repo
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add feature"
   ```
4. Push the branch:

   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request 🚀


---

> 🚀 WalmartGenie turns slow, overwhelming browsing into instant discovery—unlocking massive value for shoppers and sellers alike.
