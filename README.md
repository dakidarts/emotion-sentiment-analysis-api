
![CalcX - Emotion Sentiment Analysis API Cover](emosentbg.gif)

# 🌟 Emotion Sentiment Analysis API 🌟  
**Effortlessly unlock text insights with AI-powered sentiment and emotion analysis!**  

Welcome to the **Emotion Sentiment Analysis API**! This API provides developers with the tools to analyze text for sentiment and emotions, enabling smarter decision-making and improved user experiences.  

📢 **Subscribe now on [RapidAPI](https://rapidapi.com/kidddevs/api/emotion-sentiment-analysis-api/pricing) to get started!**  

---

## 🔥 Features  
- **Sentiment Analysis**: Detect whether text is 😊 positive, 😐 neutral, or 😠 negative in 6 languages:  
  `English (en)`, `French (fr)`, `Spanish (es)`, `German (de)`, `Portuguese (pt)`, and `Italian (it)`.  
- **Emotion Detection**: Uncover up to **28 distinct emotions** 🎭 from English text, including joy, anger, love, and more.  
- 🚀 **Fast, Reliable, and Developer-Friendly!**

---

## 📌 API Endpoints  

### 1. **`/sentiment` Endpoint**  
Analyze the sentiment of your input text across 6 languages.  
- **Input Parameters**:  
  - `text` (required): The text you want to analyze.  
- **Supported Languages**: `en`, `fr`, `es`, `de`, `pt`, `it`.  

**Sentiment Mapping**:  
| Sentiment Code | Sentiment Label |  
|----------------|----------------|  
| `0`            | Negative 😠     |  
| `1`            | Neutral 😐      |  
| `2`            | Positive 😊     |  

**Sample Request**:  
```bash
GET /sentiment?text=I love this product!
```

**Sample Response**:  
```json
{
  "input_text": "I love this product!",
  "predicted_sentiment": "Positive",
  "probability_scores": [0.1, 0.2, 0.7],
  "predicted_label": "Positive"
}
```

---

### 2. **`/emotion` Endpoint**  
Identify up to 28 distinct emotions from English text.

- **Input Parameters**:  
  - `text` (required): The text you want to analyze.  

**Emotion Mapping**:  

| Emotion Code | Emotion Label       |  
|--------------|---------------------|  
| `0`          | admiration 🥰        |  
| `1`          | amusement 😂         |  
| `2`          | anger 😡             |  
| `3`          | annoyance 😤         |  
| `4`          | approval 👍          |  
| `5`          | caring 🤗            |  
| `6`          | confusion 🤔         |  
| `7`          | curiosity 🤨         |  
| `8`          | desire 😍            |  
| `9`          | disappointment 😞    |  
| `10`         | disapproval 👎       |  
| `11`         | disgust 🤮           |  
| `12`         | embarrassment 😳     |  
| `13`         | excitement 😆        |  
| `14`         | fear 😨              |  
| `15`         | gratitude 🙏         |  
| `16`         | grief 😢             |  
| `17`         | joy 😊               |  
| `18`         | love ❤️              |  
| `19`         | nervousness 😬      |  
| `20`         | optimism 🌟          |  
| `21`         | pride 😌             |  
| `22`         | realization 🤓       |  
| `23`         | relief 😅            |  
| `24`         | remorse 😔           |  
| `25`         | sadness 😭           |  
| `26`         | surprise 😲          |  
| `27`         | neutral 😐           |  

**Sample Request**:  
```bash
GET /emotion?text=Wow I'm so excited for the weekend!
```

**Sample Response**:  
```json
{
  "input_text": "Wow I'm so excited for the weekend!",
  "predicted_emotion": "excitement",
  "probability_scores": [0.05, 0.02, 0.9, ...],
  "predicted_label": "excitement"
}
```

---

## 💻 Getting Started  
1. **Subscribe on RapidAPI**: [Emotion Sentiment Analysis API](https://rapidapi.com/kidddevs/api/emotion-sentiment-analysis-api/pricing).
2. Use the provided **API key** to authenticate your requests.
3. Start analyzing **sentiment** and **emotions** in your text data!

---

## 🤝 Contributing  
We welcome contributions! If you have suggestions or feature requests, feel free to create a [pull request](https://github.com/dakidarts/emotion-sentiment-analysis-api/pulls) or open an [issue](https://github.com/dakidarts/emotion-sentiment-analysis-api/issues).

## 📧 Contact  
For questions, feedback, or support, reach out to us via the RapidAPI platform.

---

💡 Let the Emotion Sentiment Analysis API empower your projects today! 💡
