# 📊 Instagram Friendship Analyzer

Analyze your Instagram friendships using **messages, story interactions, close friends, and favorites**.  
This project lets you upload your Instagram data export (ZIP) and discover hidden patterns in your social connections.

---

## ✨ Project Highlights
- **End-to-End Data Science Pipeline**: From raw Instagram JSON to clean DataFrames and insights.  
- **Reply Time Analytics**: Calculates **average, fastest, and slowest** reply times.  
- **Friendship Ranking**: Identify your **Top 10 Best Friends** (fastest repliers) and **Top 10 Slow Repliers** (just for fun 🐌).  
- **Story Interaction Analysis**: See which friends’ stories you liked most.  
- **Followers & Following Stats**: Explore follower/following/close friends counts.  
- **Interactive Dashboard**: Built with **Streamlit + Altair charts**.  

---

## 📂 Project Structure
```

.
├── FriendAnalyzerIG.py               # Core DS/Analytics logic (your implementation)
├── FriendAnalyzerIG\_(EnhancedUI).py  # Enhanced UI version (your logic + AI-assisted UI/UX)
└── README.md

```

### 🔑 Key Difference Between Versions
- **FriendAnalyzerIG.py**  
  - Clean, minimal UI  
  - Focused on **your original DS logic** (data wrangling, metrics, analysis)  

- **FriendAnalyzerIG_(EnhancedUI).py**  
  - Built on the same logic  
  - **AI-assisted UI enhancements**: custom CSS, animated titles, styled buttons, progress bars, polished charts  
  - Shows how the app can look in a **production-style dashboard**  

---

## 🚀 How It Works
1. **Request your Instagram data** (JSON format).  
   - Mobile: Profile → ☰ Menu → Settings → Your information → Download Your Information  
   - Desktop: Settings → Privacy & Security → Download Your Information  
   - Select **JSON** format  
2. Instagram emails you a **ZIP file**.  
3. Upload the **ZIP** into this app.  
4. Get insights on your friendships with **filters, rankings, and charts**.  

---

## 🖥️ Features Demo
🔹 *Upload your data*  
🔹 *Filter by friends or message count*  
🔹 *See top friends vs slow repliers*  
🔹 *Dive deep into one-on-one friendship insights*  

*(📸 Add screenshots here when you run the app — e.g., charts, metrics, filters)*  

---

## 📊 Example Insights
- **Best Friends (Top 10)**: Ranked by fastest reply times  
- **Slow Repliers (Top 10)**: Longest average reply times (for fun 🐍)  
- **Individual Friend Analysis**: Reply time breakdown + ranking percentile  
- **Overall Analytics**: Total messages, followers/following counts, story likes  

---

## 🔒 Privacy
- Runs **locally** in your browser session  
- Only processes **metadata** (timestamps, participants, counts)  
- Ignores **media files, ads, monetization data**  
- No data is stored or uploaded anywhere  

---

## 👨‍💻 Author
- **Sheeraz Sarwar**  
  📌 Data Science & Analytics Enthusiast  
