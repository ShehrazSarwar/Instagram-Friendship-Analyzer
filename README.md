```markdown
# 📊 Instagram Friendship Analyzer

Instagram Friendship Analyzer is a **Streamlit web app** that lets you explore and analyze your Instagram friendships using your **officially downloaded JSON data**.  
It provides fun insights like:
- 📨 **Message analysis** (counts, reply times, top friends & "snakes")
- 📖 **Story interactions** (likes on friends’ stories)
- 👥 **Followers, Following & Close Friends**
- 🎯 **Search & filter friends** with an interactive interface
- 📊 **Charts and visualizations** for reply times

---

## 🚀 Features
- **Upload your Instagram ZIP** (downloaded from Instagram Data request).
- Automatic **username detection** and ZIP validation.
- Skips **group chats** and **deactivated accounts**.
- **Reply time statistics** per friend: average, fastest, slowest.
- **Top 10 Friends** (closest by fastest replies).
- **Top 10 Snakes 🐍** (slowest to reply, just for fun).
- **Story interactions** dashboard.
- **Followers, following, and close friends** count.
- **Interactive filters** to search by individual friends.
- **Charts** built with Altair for visual insights.

---

## 📥 How to Get Your Instagram Data
1. Open **Instagram App** → Profile → **☰ Menu**.  
   Go to **Settings and privacy → Your information and permissions → Download your information**.
2. Select **All of your information** and choose **JSON** format.  
   *(You may skip Ads/Monetization files.)*
3. Instagram emails you a **ZIP file** → download it.
4. Upload the **ZIP (without unzipping)** to this app.

---

## 🛠️ Tech Stack
- **Python**
- **Streamlit** — UI framework
- **Pandas & NumPy** — data analysis
- **Altair** — charts/visualizations
- **JSON & Zipfile** — parsing Instagram data
- **Logging** — robust error handling

---

## 📂 Project Structure
```

📁 instagram-friendship-analyzer
┣ 📄 app.py              # Main Streamlit app
┣ 📄 requirements.txt    # Dependencies
┣ 📄 README.md           # Project documentation
┗ 📁 sample\_data         # (Optional) Example structure of Instagram ZIP

````

---

## ⚡ Usage
1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/instagram-friendship-analyzer.git
   cd instagram-friendship-analyzer
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```
4. Upload your Instagram ZIP and explore results 🎉

---

## 🔒 Privacy

* All analysis is done **locally in your session**.
* Media files and ad/monetization data are ignored.
* No data is uploaded to external servers.

---

## 📊 Example Insights

* **Top 10 Closest Friends** — fastest repliers.
* **Top 10 Snakes 🐍** — slowest repliers.
* **Story likes leaderboard**.
* **Reply time breakdown** for each friend (Average, Fastest, Slowest).

---

## 🏆 Why This Project?

This project demonstrates:

* Real-world **data cleaning & analysis** using Pandas/NumPy.
* Interactive **web apps** with Streamlit.
* Parsing **nested JSON from ZIP files**.
* Building **visual analytics dashboards**.
