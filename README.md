
# Amazon Data Scraper  

This Python script uses **BeautifulSoup** and **Requests** to scrape detailed product information from Amazon product pages. It's an efficient and customizable solution for extracting specific data points to support market research, competitive analysis, or other use cases.

---

## 📋 Features  

The script extracts the following product details:  
- **ASIN** (Amazon Standard Identification Number)  
- **Name** (Product Title)  
- **Price** (Current Selling Price)  
- **List Price** (Original Price)  
- **Features** (Key Product Features)  
- **Image** (Product Image URL)  
- **Rating** (Average Customer Rating)  
- **Reviews** (Number of Customer Reviews)  
- **Supplier** (Seller Name)  
- **Supplier URL** (Link to the Supplier's Store)  

---

## 🚀 How to Use  

Follow these steps to use the script effectively:  

### 1️⃣ Prerequisites  
Ensure you have Python installed on your system. Additionally, install the required libraries using the following command:  

```bash  
pip install beautifulsoup4 requests  
```  

### 2️⃣ Clone the Repository  
Clone the repository to your local machine using:  

```bash  
git clone https://github.com/hydermbs/amazonscrape.git  
cd amazon-data-scraper  
```  

### 3️⃣ Prepare the Script  
Update the script with the desired Amazon product URLs or ASINs you wish to scrape. These can typically be added to a list within the script.  

### 4️⃣ Run the Script  
Execute the script using the command:  

```bash  
python scraper.py  
```  

### 5️⃣ Output  
The scraped data will be saved as a CSV file in the output directory. You can customize the output format by modifying the script accordingly.  

---

## ⚠️ Disclaimer  

- This script is intended **for educational and personal use only.** Scraping websites like Amazon may violate their Terms of Service. Always check and comply with the site's terms before using this script.  
- Amazon employs anti-scraping mechanisms, so frequent or large-scale requests may result in IP bans or other restrictions. Consider using proxy servers or rate-limiting techniques if you're performing extensive scraping tasks.  
- This script does not bypass CAPTCHA or other advanced anti-bot systems implemented by Amazon.  

---

## 💡 Recommendations  

1. **Use Proxies:** For large-scale scraping, implement proxy rotation to prevent IP bans.  
2. **Rate Limiting:** Add delays between requests to mimic human behavior and reduce the likelihood of being flagged.  
3. **Error Handling:** Enhance the script to handle exceptions like missing data fields or network issues gracefully.  
4. **Dynamic User-Agent:** Use random user-agent strings to minimize detection risk.  

---

## 🛠️ Customization  

Feel free to customize the script to extract additional fields or modify existing logic. Contributions are always welcome—open a pull request to propose changes!  

---

## 📧 Support  

For any issues or feature requests, feel free to open an issue in this repository or reach out to me directly via GitHub.  

---

By using this script, you agree to take full responsibility for complying with all applicable laws and Amazon's policies. Use it wisely!  

---
