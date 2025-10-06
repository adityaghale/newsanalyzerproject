#  News Sentiment Analyzer



A modern Flask web app to scrape, analyze, and visualize the sentiment of news articles from any online source. Track positivity, negativity, and neutrality across your favorite news outlets in real time.

---

<div align="center">

##  Features

<table>
<tr>
  <td width="180" align="center" bgcolor="#FFEE58"><b>🔎 Analyze Any News Site</b></td>
  <td width="180" align="center" bgcolor="#81C784"><b>📊 Live Sentiment Trends</b></td>
  <td width="180" align="center" bgcolor="#BA68C8"><b>🏷️ Smart Categorization</b></td>
</tr>
</table>

</div>

---

## Tech Stack

<div align="center">

<table>
<tr>
  <td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="45"/><br/><b>Python 3.8+</b></td>
  <td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" width="45"/><br/><b>Flask</b></td>
  <td align="center"><img src="https://seeklogo.com/images/N/nltk-logo-2C9C1E91D2-seeklogo.com.png" width="45"/><br/><b>NLTK</b></td>
  <td align="center"><img src="https://raw.githubusercontent.com/codelucas/newspaper/master/images/logo.png" width="45"/><br/><b>newspaper3k</b></td>
  <td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="45"/><br/><b>HTML5</b></td>
  <td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="45"/><br/><b>CSS3</b></td>
</tr>
<tr>
  <td align="center" bgcolor="#FFF9C4"><b>BeautifulSoup4</b></td>
  <td align="center" bgcolor="#C8E6C9"><b>requests</b></td>
  <td align="center" bgcolor="#B3E5FC"><b>validators</b></td>
  <td align="center" bgcolor="#D1C4E9"><b>gunicorn</b></td>
  <td align="center" bgcolor="#ECEFF1"><b>lxml</b></td>
  <td align="center" bgcolor="#FFFDE7"><b>Jieba3k</b></td>
</tr>
</table>

</div>

---

## Screenshots

![image](https://github.com/user-attachments/assets/9fe25778-df2d-4eab-9825-9459894e7c9c)
![image](https://github.com/user-attachments/assets/1228288b-73cb-4c1b-9119-276ab1e8c54f)


---

##  Quickstart

```bash
git clone https://github.com/mithilmitmpl/news-sentiment-analyzer_new.git
cd news-sentiment-analyzer_new

# (Optional) Virtual Environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download NLTK data
python -m nltk.downloader vader_lexicon punkt

# Run the app
python app.py

# Visit: http://127.0.0.1:5001/
```

---

## Project Structure

```
.
├── app.py
├── main.js
├── render.yaml
├── LICENSE
├── README.md
└── templates/
    ├── index.html
    ├── results.html
    └── sources.html
```

---
