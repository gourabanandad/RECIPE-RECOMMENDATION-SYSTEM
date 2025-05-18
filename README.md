# 🍳 AI Recipe Recommender System

![App Screenshot](https://github.com/gourabanandad/RECIPE-RECOMMENDATION-SYSTEM/blob/main/demo.png)
 *(Example screenshot placeholder)*

> **Smart recipe suggestions based on ingredients you have**  
> Built with Python Flask backend + Modern Frontend (No frameworks)

## 🚀 Quick Start

1. **Clone & Install**:
   ```bash
   git clone https://github.com/gourabanandad/RECIPE-RECOMMENDATION-SYSTEM.git
   cd recipe-recommender
   pip install -r requirements.txt
   ```

2. **Run the App**:
   ```bash
   python main.py
   ```

3. **Open in Browser**:

   [http://localhost:5001(Local Host)](http://localhost:5001)

   [See the live website](https://recipe-recommendation-system-7obk.onrender.com/)

---

## 🔥 Key Features

- **Smart Matching** - Finds recipes using cosine similarity
- **Beautiful UI** - Modern design with animations
- **One-Click Access** - Direct links to recipe sources
- **Responsive** - Works on all devices
- **No Database Needed** - Uses CSV dataset (auto-downloaded on first run)

---

## 📦 Files Overview

| File/Folder     | Purpose                         |
|----------------|---------------------------------|
| `main.py`      | Flask backend server            |
| `static/`      | Frontend files (HTML/CSS/JS)    |
| `dataset/`     | Recipe data in CSV format       |
| `requirements.txt` | Python dependencies         |

---

## 📌 Requirements

- Python 3.8+
- Modern web browser

---

## 🌟 Why This Project?

- Perfect for home cooks
- Reduces food waste
- No complex setup
- Easy to customize

---

## 📚 Dataset Format

CSV:
```csv
title,ingredients,directions,link,NER
"Pasta Carbonara","['pasta','eggs','bacon']","['Boil pasta','Mix eggs']","https://example.com","pasta eggs bacon"
```

> ⚠️ You don't need to worry about the dataset — it is automatically downloaded when you run `main.py`.

---

## 🛠️ Troubleshooting

**Q: Links not showing?**  
**A:** Ensure your CSV has a `link` column

**Q: Getting CORS errors?**  
**A:** Verify `flask-cors` is installed

**Q: No recipes found?**  
**A:** Check dataset path in `main.py`

---

## 📜 License

MIT License - Free for personal and commercial use

---

Enjoy cooking! 👨‍🍳  
Star the repo if you find this useful! ⭐

