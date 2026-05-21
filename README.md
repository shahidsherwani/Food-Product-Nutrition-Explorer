# Food Product & Nutrition Explorer

## Description
A Flask web application that allows users to search food products by name, brand, or barcode
using the Open Food Facts API. Displays nutrition facts, ingredients, allergens, Nutri-Score,
product origins, and enables comparison of multiple products.

## Features (Must-Have)
- Product search by name, brand, or barcode
- Display ingredients, allergens, Nutri-Score, and nutrition table
- Compare at least 2-3 products with charts
- Show product origin countries on a Folium map
- Save products to SQLite database (favorites/history)

## Features (Nice-to-Have)
- Barcode scanner (webcam)
- Export comparison to PDF
- Dark/Light mode toggle

## Technologies Used
- Flask (web framework)
- SQLite3 (backend database)
- Open Food Facts API (product data)
- REST Countries API (country information)
- Folium (interactive maps)
- Plotly/Matplotlib (charts and visualizations)
- HTML/CSS/Bootstrap (frontend)

#### Project Structure

```text
Food-Product-Nutrition-Explorer/
├── app.py              # Main Flask application
├── api_handler.py      # API integration (Open Food Facts, REST Countries)
├── requirements.txt    # Python dependencies
├── .gitignore          # Git ignore rules
├── templates/
│   ├── index.html      # Home page with search form
│   ├── product.html    # Product detail page
│   ├── compare.html    # Product comparison page
│   └── map.html        # Country map page
└── static/
    ├── css/
    └── js/
```

## Setup & Installation
1. Clone the repository
2. Create virtual environment: `python -m venv venv`
3. Activate: `source venv/bin/activate` (or `venv\Scripts\activate` on Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Run the app: `python app.py`
6. Open browser: `http://127.0.0.1:5000`

## APIs planned
- **Open Food Facts API**: https://openfoodfacts.github.io/openfoodfacts-server/api/ — Product search by name/barcode
- **REST Countries API**: https://restcountries.com — Country information for mapping

## Task Distribution
| Member | Responsibilities |
|--------|-----------------|
| Sameer Kulkarni | API integration, JSON parsing, templates,  Plotly/Matplotlib (charts and visualizations)|
| Shahid Sherwani | Flask (web framework), SQLite database, Folium (interactive maps) |
, charts, Folium map |

