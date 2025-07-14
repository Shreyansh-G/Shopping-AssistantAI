# 🛒 WalmartGenie – Your AI Shopping Companion

[![Demo Video](https://img.youtube.com/vi/TFmY_R624Ew/0.jpg)](https://www.youtube.com/watch?v=TFmY_R624Ew)


WalmartGenie is an **AI-powered shopping assistant** that helps users instantly discover **hidden gems**, trending picks, best deals, and try on fashion items virtually — all within seconds.

Built for the **Walmart Sparkathon**, WalmartGenie transforms the Walmart shopping experience with smart recommendations and intuitive browsing.

---

## 🚨 The Problem

Millions of quality products on Walmart go undiscovered due to poor visibility:

- 🧭 50% of users don’t go past page 2.
- 📉 60% of great products go unsold.
- 💔 35% of online sellers fail within 120 days.
- 💸 Discovery issues cost retailers **>$369B/year**.

---

## 💡 Our Solution: WalmartGenie

A blazing-fast AI shopping assistant that understands natural language queries like:

> “Running shoes under $100 for flat feet”

It delivers laser-targeted suggestions powered by OpenAI + curated product data.

### 🔍 Key Features

| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| 💎 Hidden Gems       | High-rated, low-visibility items (Core innovation)                          |
| 📈 Trending Picks    | Items gaining traction via real-time trend signals                         |
| 💰 Value Deals       | Top 8 products with the **steepest discounts**                              |
| 👗 Virtual Try-On    | AR previews for fashion & beauty items (via Gemini Vision + Expo)          |
| 🤖 Smart Alternatives| AI-suggested swaps with similar ratings, categories, and budgets            |

---

## ⚙️ Tech Stack

- **Frontend:** React Native + Gifted Chat UI
- **Backend:** Node.js, Express.js, MongoDB, Firebase
- **AI/NLP:** OpenAI GPT API for conversation and understanding
- **Data Layer:** Firebase + JSON product model with discount %, rating, flags
- **AR Experience:** Expo + AR + Gemini Vision APIs (Virtual Try-On)

---

## 📊 Impact

| Metric                    | Result                          |
|---------------------------|----------------------------------|
| 🛍️ Conversion Lift         | +23% (Glassix, 2024)             |
| 🔁 Repeat Visits           | +61% (Forrester, 2023)           |
| ⏱️ Faster Purchase Time    | 30% reduction in decision time   |

WalmartGenie doesn’t just save time—it **rescues great products from being ignored**.

---

## Setup Instructions

### 1. Install Dependencies
```bash
npm install
```

### 2. Environment Configuration
Create a `.env` file in the root directory:
```
FIREBASE_API_KEY=
OPENAI_API_KEY=
GOOGLE_CLOUD_API_KEY=
```

Get  Gemini API key:
1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Add it to your `.env` file

Get OpenAI API Key
1.Go to OpenAI API Dashboard
2.Click "Create new secret key"
3.Copy and paste it into the OPENAI_API_KEY field in your .env

Get Firebase API Key
1.Go to Firebase Console
2.Create a new project (or select an existing one)
3.Click Project Settings > General
4.Under "Your apps", register your app and find your Firebase config
5.Copy the apiKey field and paste it into FIREBASE_API_KEY in your .env

Note:⚠️ Don’t forget to enable Firestore and configure basic security rules.
### 3. Run the Application
```bash
npm start
```

Then press:
- `a` for Android
- `i` for iOS
- `w` for web

## Project Structure

```
drippy/
├── components/
│   └── WalmartChatbot.tsx      # AI chatbot component
├── screens/
│   ├── HaulScreen.tsx          # Main shopping screen
│   ├── ProductDetailScreen.tsx  # Product details
│   ├── TryingRoomScreen.tsx    # AR try-on feature
│   └── WardrobeScreen.tsx      # Saved items
├── utils/
│   ├── walmartDataSource.ts    # Walmart data handling
│   └── dataSource.ts          # Legacy data source
├── navigation/
│   └── index.tsx              # App navigation
└── assets/
    └── dataset/
        └── walmart-products.csv # Walmart product dataset
```

---

## Key Technologies

- **React Native**: Cross-platform mobile development
- **Expo**: Development platform and tools
- **Google Gemini AI**: Advanced AI chatbot
- **TypeScript**: Type-safe development
- **NativeWind**: Tailwind CSS for React Native
- **React Navigation**: Navigation framework

---

## 📬 Features


### 🛍️ Shopping Experience
- **Walmart Product Integration**: Full integration with Walmart product dataset
- **Modern UI**: Clean, modern interface with shopping-focused design
- **Product Discovery**: Browse products by categories, tags, and search
- **Featured Products**: Curated collections of top-rated and discounted items
- **Product Details**: Comprehensive product information with size/color selection

### 🤖 AI Chatbot Assistant
- **Gemini AI Powered**: Advanced conversational AI using Google's Gemini API
- **Product Recommendations**: Smart product suggestions based on user queries
- **Shopping Assistance**: Help with product searches, deals, and category browsing
- **Floating Interface**: Easy-to-access chatbot button on home screen
- **Real-time Responses**: Instant AI-powered responses with product cards

### 🎯 Unique Selling Points
- **Virtual Try-On**: AR-powered trying room for clothing items
- **Personalized Wardrobe**: Save and organize favorite items
- **Smart Recommendations**: AI-driven product suggestions
- **Modern Shopping Experience**: Seamless integration of AI and e-commerce

---



## 🤝 Contributing

We welcome contributions from developers, designers, and data enthusiasts!

To contribute:

1. Fork the repo
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit: `git commit -m "Add feature"`
4. Push to the branch: `git push origin feature-name`
5. Create a pull request!

---

## 👥 Contributors

| Name              
|-------------------
| [Jatin Narayan]
| [Shreyansh Gupta]
| [Shashank Panday]
| [Satyendra Singh]

---

## 🏁 Built for Walmart Sparkathon 2025

This project was submitted to the **Walmart Sparkathon** — reimagining how shoppers discover products at scale.

---

## 📽️ Watch the Demo

Click the thumbnail above or [watch on YouTube]([https://www.youtube.com/watch?v=TFmY_R624Ew])


> 🚀 WalmartGenie turns slow, overwhelming browsing into instant discovery—unlocking massive value for shoppers and sellers alike.





