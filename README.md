# **Automating Crypto API Pull Using Python**  

🚀 A Python-based automation script to fetch real-time cryptocurrency data from the **CoinMarketCap API**, normalize it into a DataFrame, and visualize price trends.  

## **📌 Features**  
✅ Automates API calls to fetch the latest cryptocurrency data  
✅ Parses and normalizes JSON data into a Pandas DataFrame  
✅ Appends new data dynamically for historical tracking  
✅ Analyzes and visualizes price trends using **Matplotlib** & **Seaborn**  
✅ Tracks price changes over time for selected cryptocurrencies  

## **🔑 API Key Setup**  

To use the **CoinMarketCap API**, you need an API key.  

1. Sign up at [CoinMarketCap API](https://coinmarketcap.com/api/)  
2. Generate an API key  
3. Replace the placeholder in `Automating Crypto Website API Pull Using Python.ipynb`:  

```python
API_KEY = "your-api-key-here"
```

## **📊 Visualizations**  

The script generates two key visualizations:  

1. **Percentage Price Change Analysis**  
   - Tracks changes over different timeframes (1h, 24h, 7d, 30d, etc.).  
   - Displays results using a **Seaborn point plot**.  

2. **Bitcoin Price Trend**  
   - Extracts Bitcoin price history and visualizes it using a **Seaborn line plot**.  

## **📚 Resources**  
- **CoinMarketCap**: [https://coinmarketcap.com/](https://coinmarketcap.com/)  
- **CoinMarketCap API**: [https://coinmarketcap.com/api/](https://coinmarketcap.com/api/)  
- **API Documentation**: [https://coinmarketcap.com/api/documentation/](https://coinmarketcap.com/api/documentation/)  

---
