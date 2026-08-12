# Awesome APIs 🚀 

> A curated list of awesome APIs for developers. Perfect for building applications, prototyping, and learning.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/AkashYadav8080/awesome-apis.svg?style=social&label=Star)](https://github.com/username/awesome-apis)
[![GitHub forks](https://img.shields.io/github/forks/AkashYadav8080/awesome-apis.svg?style=social&label=Fork)](https://github.com/username/awesome-apis)

## 📋 Table of Contents

- [Weather APIs](#weather-apis)
- [News APIs](#news-apis)
- [Location & IP APIs](#location--ip-apis)
- [Development & Testing APIs](#development--testing-apis)
- [Space & Science APIs](#space--science-apis)
- [Utility APIs](#utility-apis)
- [Entertainment APIs](#entertainment-apis)
- [Finance APIs](#finance-apis)
- [AI & Machine Learning APIs](#ai--machine-learning-apis)
- [Translation APIs](#translation-apis)
- [Search APIs](#search-apis)
- [API Marketplaces](#api-marketplaces)
- [Contributing](#contributing)
- [License](#license)

## 🌤️ Weather APIs

### WeatherStack
**Real-Time & Historical World Weather Data API**
- **URL**: https://weatherstack.com/
- **Description**: Retrieve instant, accurate weather information for any location in the world in lightweight JSON format
- **Features**: Current weather, historical data, weather forecasts
- **Pricing**: Free tier available (1,000 requests/month)
- **Authentication**: API Key required
- **Rate Limits**: Varies by plan

```bash
# Example usage
curl "http://api.weatherstack.com/current?access_key=YOUR_API_KEY&query=New York"
```

## 📰 News APIs

### NewsAPI
**Search worldwide news with code**
- **URL**: https://newsapi.org/
- **Description**: Get breaking news headlines and search for articles from news sources and blogs across the websites
- **Features**: Breaking news, everything articles, top headlines, sources
- **Pricing**: Free tier (1,000 requests/day), paid plans available
- **Authentication**: API Key required
- **Rate Limits**: 1,000 requests per day (free tier)

```javascript
// Example usage
fetch('https://newsapi.org/v2/top-headlines?country=us&apiKey=YOUR_API_KEY')
  .then(response => response.json())
  .then(data => console.log(data));
```

### MediaStack
**Global News Data Free, Simple REST API**
- **URL**: https://mediastack.com/
- **Description**: Scalable JSON API for live news and blog articles from around the world
- **Features**: Live news, historical news, news sources, news search
- **Pricing**: Free tier available (500 requests/month)
- **Authentication**: API Key required
- **Rate Limits**: Varies by plan

## 🌍 Location & IP APIs

### IPAPI
**IP Address Location API**
- **URL**: https://ipapi.co/
- **Description**: Find IP address location including city, country, postal code, latitude, and longitude
- **Features**: IP geolocation, ISP information, threat detection
- **Pricing**: Free tier (1,000 requests/day), paid plans available
- **Authentication**: API Key (optional for free tier)
- **Rate Limits**: 1,000 requests per day (free tier)

```python
# Example usage
import requests
response = requests.get('https://ipapi.co/8.8.8.8/json/')
print(response.json())
```

## 🔧 Development & Testing APIs

### APIWatch

- **Description**: API health monitoring and alerting. Track uptime, response times, and get notified when APIs go down.
- **Base URL**: https://carey-omaha-resume-kitty.trycloudflare.com
- **Category**: Monitoring, DevOps, Developer Tools
- **Pricing**: Free (open source)
- **Authentication**: None
- **Rate Limits**: None
- **GitHub**: https://github.com/155143783/apiwatch

### JSONPlaceholder
**Free fake and reliable API for testing and prototyping**
- **URL**: https://jsonplaceholder.typicode.com/
- **Description**: Fake online REST API for testing and prototyping
- **Features**: Posts, comments, albums, photos, todos, users
- **Pricing**: Completely free
- **Authentication**: Not required
- **Rate Limits**: None

```javascript
// Example usage
fetch('https://jsonplaceholder.typicode.com/posts/1')
  .then(response => response.json())
  .then(json => console.log(json))
```

## 🚀 Space & Science APIs

### NASA API
**Welcome to the NASA API portal**
- **URL**: https://api.nasa.gov/
- **Description**: Access to NASA's image and video library, including imagery from the Mars rovers
- **Features**: APOD, Mars Rover Photos, Earth Imagery, Exoplanet Archive
- **Pricing**: Free with API key
- **Authentication**: API Key required (free)
- **Rate Limits**: 1,000 requests per hour

```bash
# Example usage - Astronomy Picture of the Day
curl "https://api.nasa.gov/planetary/apod?api_key=YOUR_API_KEY"
```

## 🛠️ Utility APIs

### QR Server API
**QR Code Generator and Reader API**
- **URL**: https://goqr.me/api/
- **Description**: Generate and decode QR code graphics via web API
- **Features**: QR code generation, QR code reading, various formats
- **Pricing**: Free
- **Authentication**: Not required
- **Rate Limits**: Fair usage policy

```html
<!-- Example usage - Generate QR Code -->
<img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=Hello World" alt="QR Code" />
```

### Advice Slip API
**Random advice generator**
- **URL**: https://api.adviceslip.com/
- **Description**: Get random pieces of advice in JSON format
- **Features**: Random advice, search advice, advice by ID
- **Pricing**: Free
- **Authentication**: Not required
- **Rate Limits**: None specified

```javascript
// Example usage
fetch('https://api.adviceslip.com/advice')
  .then(response => response.json())
  .then(data => console.log(data.slip.advice));
```

### Open Trivia Database
**Free trivia questions API**
- **URL**: https://opentdb.com/api_config.php
- **Description**: Free JSON API for trivia questions, perfect for quiz applications
- **Features**: Multiple categories, difficulty levels, question types
- **Pricing**: Free
- **Authentication**: Not required
- **Rate Limits**: 5 seconds between requests

## 🎬 Entertainment APIs

### GIPHY API
**GIF and Sticker API**
- **URL**: https://developers.giphy.com/docs/
- **Description**: Access GIPHY's library of animated GIFs and stickers
- **Features**: Search GIFs, trending GIFs, random GIFs, stickers
- **Pricing**: Free tier available, paid plans for higher limits
- **Authentication**: API Key required
- **Rate Limits**: Varies by endpoint and plan

```javascript
// Example usage
fetch('https://api.giphy.com/v1/gifs/search?api_key=YOUR_API_KEY&q=cats&limit=10')
  .then(response => response.json())
  .then(data => console.log(data));
```

## 💰 Finance APIs

### x402 Data API

- **Description**: HTTP 402 micro-payment Data API on Base chain. Pay per request with USDC.
- **Base URL**: https://charleston-friendship-contributors-wallpapers.trycloudflare.com
- **Category**: Finance, Crypto, Developer Tools
- **Pricing**: $0.001-0.01 per request (USDC on Base)
- **Authentication**: x402 protocol (HTTP 402 payment)
- **Rate Limits**: None (payment-gated)
- **GitHub**: https://github.com/155143783/x402-data-api

### Exchange Rates API
**Free currency exchange rates**
- **URL**: https://exchangerate.host/documentation
- **Description**: Reliable currency exchange rates and currency conversion
- **Features**: Live rates, historical data, currency conversion, time series
- **Pricing**: Free
- **Authentication**: Not required
- **Rate Limits**: None specified

```javascript
// Example usage
fetch('https://api.exchangerate.host/latest?base=USD&symbols=EUR,GBP')
  .then(response => response.json())
  .then(data => console.log(data));
```

## 🤖 AI & Machine Learning APIs

### Google Gemini API
**Google's AI API**
- **URL**: https://ai.google.dev/gemini-api/docs
- **Description**: Access Google's Gemini AI models for text generation and analysis
- **Features**: Text generation, content analysis, multi-modal capabilities
- **Pricing**: Free tier available, usage-based pricing
- **Authentication**: API Key required
- **Rate Limits**: Varies by model and plan

### Genderize.io
**Gender prediction from names**
- **URL**: https://genderize.io/
- **Description**: Predict the gender of a person based on their first name
- **Features**: Gender prediction, probability scores, country-specific data
- **Pricing**: Free tier (100 requests/day), paid plans available
- **Authentication**: API Key (optional)
- **Rate Limits**: 100 requests per day (free tier)

```bash
# Example usage
curl "https://api.genderize.io/?name=peter"
```

## 🔤 Translation APIs

### LibreTranslate
**Free and Open Source Translation API**
- **URL**: https://libretranslate.com/
- **Description**: Self-hosted translation API that doesn't rely on proprietary providers
- **Features**: Text translation, language detection, multiple language pairs
- **Pricing**: Free (self-hosted), hosted plans available
- **Authentication**: API Key (for hosted version)
- **Rate Limits**: Varies by deployment

```python
# Example usage
import requests
response = requests.post('https://libretranslate.de/translate', {
    'q': 'Hello World',
    'source': 'en',
    'target': 'es'
})
print(response.json())
```

## 🔍 Search APIs

### SerpApi
**Google Search API**
- **URL**: https://serpapi.com/
- **Description**: Scrape Google Search Results via API
- **Features**: Google Search, Google Images, Google News, Google Shopping
- **Pricing**: Free tier (100 searches/month), paid plans available
- **Authentication**: API Key required
- **Rate Limits**: Varies by plan

## 🏪 API Marketplaces

### RapidAPI
**World's largest public API Hub**
- **URL**: https://rapidapi.com/
- **Description**: Discover, test, and connect to thousands of APIs
- **Features**: API marketplace, unified billing, API testing tools
- **Pricing**: Varies by API
- **Authentication**: RapidAPI key required
- **Rate Limits**: Varies by API

### Public APIs Collection
**Comprehensive list of public APIs**
- **URL**: https://github.com/public-apis/public-apis
- **Description**: A collective list of free APIs for use in software and web development
- **Features**: Categorized API list, community-maintained, regular updates
- **Pricing**: Free (repository)
- **Authentication**: Varies by API
- **Rate Limits**: Varies by API

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to contribute:
1. Fork this repository
2. Add your API to the appropriate category
3. Follow the format guidelines
4. Submit a pull request

### API Entry Format:
```markdown
### API Name
**Brief description**
- **URL**: https://testapp.com/
- **Description**: Detailed description of what the API does
- **Features**: Key features and capabilities
- **Pricing**: Pricing information
- **Authentication**: Authentication requirements
- **Rate Limits**: Rate limiting information
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💗 Support

Found it helpful? Give it a star ⭐ and consider contributing by sharing your favorite APIs.

---

**Disclaimer**: API availability, pricing, and terms may change. Please check the official documentation for the most up-to-date information. 
