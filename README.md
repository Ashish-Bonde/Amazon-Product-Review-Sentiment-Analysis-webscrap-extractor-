# 🛠️ **Amazon Product Review Extractor & Sentiment Analysis Tool**

## 🔍 Overview

The **Amazon Product Review Extractor and Sentiment Analysis Tool** is a Python-based web application that allows users to extract product reviews from Amazon and perform sentiment analysis using the **VADER (Valence Aware Dictionary and sEntiment Reasoner)** model.

This tool helps businesses, researchers, and individuals understand customer opinions by analyzing review content and visualizing sentiment in an intuitive way using **Streamlit**, **BeautifulSoup**, and **Plotly Express**.

---

## 🎯 Features

- ✅ **Amazon Review Extraction**
  - Extract customer names, dates, star ratings, short and long reviews.
- ✅ **Sentiment Analysis**
  - Analyze reviews using VADER for Positive, Neutral, or Negative classification.
- ✅ **Multiple Input Sources**
  - Use extracted Amazon reviews
  - Upload your own CSV file
  - Paste a public Google Sheet link
- ✅ **Interactive Visualizations**
  - Pie Chart: Overall sentiment distribution
  - Histogram: Sentiment across columns
  - Scatter Plot: Sentiment vs other features
- ✅ **Data Export**
  - Download extracted and analyzed data as CSV files

---

## 🛠️ Technologies Used

| Layer | Technology |
|-------|------------|
| **Frontend** | Streamlit |
| **Backend** | Python |
| **Web Scraping** | BeautifulSoup + Requests |
| **NLP Engine** | VADER Sentiment |
| **Data Visualization** | Plotly Express |
| **Data Handling** | Pandas |

---

## 📁 Project Structure

```
amazon-review-analyzer/
│
├── app.py                      # Main application entry point
└── requirements.txt            # List of required Python packages
```

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

### `requirements.txt` includes:
```
streamlit==1.43.2
beautifulsoup4==4.12.3
vadersentiment==3.3.2
pandas==2.2.3
plotly==5.26.0
nltk==3.9
requests==2.32.3
```

---

## ▶️ How to Run Locally

# Clone the repository
```
git clone https://github.com/Ashish-Bonde/Amazon-Product-Review-Sentiment-Analysis-webscrap-extractor-.git
```
# Navigate into the project directory
cd Amazon-Product-Review-Sentiment-Analysis-webscrap-extractor-


2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run app.py
   ```

4. Open your browser and go to:
   ```
   http://localhost:8501
   ```

---

## 🌐 Live Demo

🔗 [View the deployed app on Streamlit Cloud][https://amazon-review-analyzer.streamlit.app/](https://amazon-review-extractor-and-sentiment-analyser.streamlit.app/)
---
```
https://amazon-review-extractor-and-sentiment-analyser.streamlit.app/
```
---

## 💡 Use Cases

- **Business Intelligence**: Understand customer satisfaction with products.
- **Marketing Strategy**: Identify trends and improve marketing campaigns.
- **Academic Research**: Study consumer behavior and sentiment patterns.
- **Personal Use**: Help decide whether to buy a product based on aggregated sentiment.

---
# 💡 Advantages of This Tool

| Feature | Description |
|---------|-------------|
| 🌐 **Cloud-Based** | No installation needed; just open link in any browser. |
| 📥 **File Upload Support** | Analyze sentiment from local CSV files. |
| 📄 **Google Sheets Integration** | Paste a shareable Google Sheet link for live analysis. |
| 🤖 **NLP-Powered Sentiment Analysis** | Uses VADER for quick and accurate sentiment classification. |
| 📊 **Interactive Visualizations** | Understand customer opinions visually with Plotly charts. |
| 📦 **Data Export** | Save both raw and analyzed data as CSV for further use. |


---
## 🚨 Limitations

- Amazon frequently updates its website structure – scraping may break if HTML changes.
- Some pages require login or JavaScript rendering which this tool does not support.
- VADER is best suited for social media texts; may not capture nuanced product sentiment accurately.

---

## 🚀 Future Enhancements

- Replace VADER with BERT or RoBERTa models for better accuracy.
- Add multi-column sentiment analysis.
- Implement automated pagination detection for multiple review pages.
- Add PDF and Excel export options.
- Integrate cloud storage (e.g., Firebase or AWS S3) for persistent user uploads.
- Add authentication system for saving preferences/history.

---

## 👨‍💻 Developer Info

- **Name:** Ashish Bonde  
- **GitHub:** [github.com/Ashu-TheCoder](https://github.com/Ashu-TheCoder)  
- **LinkedIn:** [linkedin.com/in/ashish-bonde](https://www.linkedin.com/in/ashish-bonde/)  
- **WhatsApp:** [+91 8484864084](https://api.whatsapp.com/send?phone=918484864084&text=Hi%20Ashish!%20I'm%20interested%20in%20your%20Amazon%20Review%20Extractor%20and%20Sentiment%20Analysis%20Tool.%20Let's%20connect!)  

---

## 📝 License

MIT License – see the [LICENSE](LICENSE) file for details.

---

## 🙌 Contributing

Contributions are welcome! Feel free to open issues or pull requests for improvements, bug fixes, or new features.

---

## 📬 Feedback

If you have any suggestions or need help with deployment/customization, feel free to reach out!

---

**Thank you for checking out the Amazon Product Review Extractor and Sentiment Analysis Tool!**  
We hope it helps you gain valuable insights from customer feedback. 😊
