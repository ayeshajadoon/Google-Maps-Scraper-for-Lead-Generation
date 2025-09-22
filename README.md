# 🗺️ Google Maps Scraper for Lead Generation

A **Python-based Google Maps Scraper** that automates business data extraction from Google Maps for **lead generation, marketing, and outreach**.  
It gathers structured business information such as name, address, phone number, ratings, and website links, and stores them in a CSV file.

---

## ⚡ Features
- 🔍 Extracts thousands of business leads efficiently.  
- 📋 Collects details such as:  
  - Business Name  
  - Address  
  - Contact Number  
  - Ratings & Reviews  
  - Website (if available)  
- 💾 Saves results into a **CSV file**.  
- 🛠️ Built with **Selenium, BeautifulSoup, Requests, and Pandas**.  
- ☁️ Can be run locally or on **Google Colab** (Chrome & ChromeDriver setup included).  

---

## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/google-maps-scraper.git
cd google-maps-scraper
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
Or install manually:
```bash
pip install selenium beautifulsoup4 requests pandas
```

### 3. (For Google Colab Users) Setup Chrome & ChromeDriver
The script includes commands to install Chromium and ChromeDriver automatically:
```bash
os.system('apt-get update > /dev/null 2>&1')
os.system('apt install chromium-chromedriver > /dev/null 2>&1')
os.system('cp /usr/lib/chromium-browser/chromedriver /usr/bin')
```

## 🚀 Usage

1. Open the script Jupyter/Colab notebook.  
2. Enter your **search keyword** (e.g., `"dentists in New York"`).  
3. Run the scraper, it will:  
   - Open Google Maps  
   - Scroll through the search results  
   - Extract business data  
4. The results will be saved automatically in a file named **`leads.csv`**.  


## ⚠️ Disclaimer

This project is for educational purposes only.
Scraping Google Maps may violate Google’s Terms of Service. Please use responsibly and ensure compliance with local laws before deploying for commercial use.


## 📧 Contact

**👩‍💻 Developer:** Ayesha Khan  
**🔗 LinkedIn:** [Your LinkedIn Profile](www.linkedin.com/in/ayeshajadoon)  
**📩 Email:** ayesha.k.jadoon@gmail.com  
