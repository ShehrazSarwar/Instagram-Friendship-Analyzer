# 📊 Instagram Friendship Analyzer

**Instagram Friendship Analyzer** is an interactive **Streamlit app** that processes your official **Instagram data download (JSON ZIP)** and reveals fun insights about your friendships.

It shows:

* 📨 **Message analysis** — counts, reply times, and conversation stats.
* 🏆 **Top 10 Friends & Top 10 Snakes** 🐍 (just for fun).
* 📖 **Story interactions** — who you liked most.
* 👥 **Followers, Following, and Close Friends** overview.
* 🎯 **Search & filter options** for exploring friendships individually.

---

## 🚀 Features

* Upload your **Instagram ZIP** (downloaded via *Download Your Information* request).
* Detects **username** automatically from ZIP.
* Skips **group chats** & **deactivated accounts** for cleaner results.
* Reply time statistics: **average, fastest, slowest**.
* Interactive **charts & tables** using Altair + Pandas.
* Story likes breakdown and **friend-specific dashboards**.

---

## 📥 How to Get Your Instagram Data

1. Open **Instagram App** → Profile → **☰ Menu**.
   Go to **Settings and privacy → Your information and permissions → Download your information**.
2. Select **All of your information** → choose **JSON** format.
   *(You can skip Ads/Monetization files.)*
3. Instagram emails you a **ZIP file**.
4. Upload the ZIP (without unzipping) into this app.

---

## 🛠️ Tech Stack

* **Python 3**
* **Streamlit** — web app framework
* **Pandas & NumPy** — data analysis
* **Altair** — charts and visualizations
* **JSON + Zipfile** — parsing Instagram export data
* **Logging** — robust error handling

---

## 📂 Project Structure

```
📁 instagram-friendship-analyzer
 ┣ 📄 app.py              # Main Streamlit app
 ┣ 📄 README.md           # Project documentation
```

## 📊 Example Insights

* **Top 10 Closest Friends** — fastest repliers.
* **Top 10 Snakes 🐍** — slowest repliers (for fun).
* **Story Likes Leaderboard** — friends you interact with most.
* **Individual Friend Dashboard** — reply breakdown + charts.

---

## 🔒 Privacy

* All analysis is done **locally in your session**.
* Media files and ads data are ignored.
* Nothing is uploaded or stored externally.
