# 🔍 OLX Parser

An asynchronous parser for OLX.ua advertisements with Excel export.  
Fast data loading with automatic formatting and saves every 2 pages.  
Built with **aiohttp**, **openpyxl**, and async/await architecture.

## ✨ Key Features

- Asynchronous data loading via API
- Excel export with formatting (width 240px, height 160px)
- Auto-save every 2 pages
- Random delay between requests (3-6 sec)
- Colored progress output in console
- Collects: ID, title, URL, description, price, location, photos, seller info

## 🚀 Installation

```bash
git clone https://github.com/your-username/olx-parser.git
cd olx-parser
pip install -r requirements.txt
```

### Run the Parser

```bash
python main.py
```

The script will create an `olx_offers.xlsx` file with all collected data.

## 📊 Example Output

```
Страница 1: 40 объявлений → Задержка 4.3с
Страница 2: 40 объявлений → Задержка 5.1с
```

## 📄 License

GPL-3.0 license 

---

⭐ If you find this project useful, consider giving it a star!  
Happy parsing! 🚀

---


