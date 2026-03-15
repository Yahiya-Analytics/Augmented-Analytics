# 📊 Augmented Analytics

> **Go from a raw CSV file to boardroom-ready insights — without writing a single line of code.**

Most data analysis tools still require you to know what questions to ask, which charts to build, and how to clean messy data before you begin. **Augmented Analytics** eliminates all three barriers by deploying a team of four specialized AI agents that handle the entire workflow automatically — from dirty data to decision-ready insights, in seconds.

---

## 🧩 The Problem → The Solution

| Problem | Augmented Analytics Solution | Result |
|---|---|---|
| Raw CSVs are messy and unreliable | The Cleaner agent fixes nulls, types, and inconsistencies automatically | Analysis-ready data in **under 5 seconds** |
| You don't know where to start with a new dataset | The Profiler agent maps the full statistical landscape for you | Instant health report — distributions, correlations, outliers |
| Translating data into business insight is slow | The Analyst agent surfaces patterns, anomalies, and key findings | Actionable conclusions without manual exploration |
| Building the right chart takes trial and error | The Visualizer agent generates charts — or you describe what you want in plain English | Perfect visualization on the **first try** |

---

## 🤖 Meet the Four Agents

The core innovation is not a single AI model — it's a **coordinated pipeline of four specialists**, each with a defined role:

```
Raw CSV File Uploaded
        │
        ▼
┌───────────────────────────────────┐
│  🧹  THE CLEANER                  │
│  Handles missing values,          │
│  fixes data types, removes        │
│  duplicates, standardizes formats │
└────────────────┬──────────────────┘
                 │ Clean Data
                 ▼
┌───────────────────────────────────┐
│  🔍  THE PROFILER                 │
│  Generates a full statistical     │
│  report: distributions, nulls,    │
│  correlations, outlier flags      │
└────────────────┬──────────────────┘
                 │ Data Profile
                 ▼
┌───────────────────────────────────┐
│  🧠  THE ANALYST                  │
│  Interprets the profile,          │
│  identifies patterns, anomalies,  │
│  and key business signals         │
└────────────────┬──────────────────┘
                 │ Insights
                 ▼
┌───────────────────────────────────┐
│  📈  THE VISUALIZER               │
│  Auto-generates the best charts   │
│  OR builds from your plain-       │
│  English description via chat     │
└───────────────────────────────────┘
        │
        ▼
Dashboard: Insights · Charts · What-If Simulation
```

---

## ✨ Key Features

**🤖 Automated End-to-End Analysis**
Upload any CSV. The four-agent pipeline runs automatically — no configuration, no column mapping, no setup required.

**💬 Conversational Visualization**
Don't know which chart you need? Just describe it: *"Show me revenue by region as a bar chart"* or *"Compare Q1 vs Q2 sales trends"* — the Visualizer agent builds it from your plain English.

**🔮 What-If Simulation**
Model the impact of business decisions before making them. Change input variables and see projected outcomes update in real time — without touching a spreadsheet.

**0️⃣ Lines of Code Required**
The entire journey from raw data to decision is handled by the agents. You interact through a clean web interface, not a notebook or terminal.

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Frontend / UI | [Streamlit](https://streamlit.io) |
| AI Agents | [Google Gemini API](https://ai.google.dev) |
| Data Processing | Python · Pandas |
| Visualization | Plotly / Matplotlib |
| Orchestration | Multi-agent pipeline |

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.8+
- A [Google Gemini API key](https://ai.google.dev)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Yahiya-Analytics/Augmented-Analytics.git
cd Augmented-Analytics

# 2. Install dependencies
pip install -r requirements.txt

# 3. Set up your environment variables
# Create a .env file in the root directory and add:
echo 'GOOGLE_API_KEY="your_api_key_here"' > .env

# 4. Launch the app
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

---

## 🚀 How to Use

1. **Upload** — Drop in any CSV file (sales data, customer records, survey results, etc.)
2. **Watch** — The four agents run automatically: clean → profile → analyse → visualize
3. **Explore** — Browse your auto-generated insights and charts on the dashboard
4. **Chat** — Use the conversational interface to request custom visualizations
5. **Simulate** — Use the What-If panel to model different business scenarios

---

## 🎯 Example Use Cases

- **Sales Managers** identifying revenue leaks across regions without needing a data team
- **Startup Founders** getting instant answers from user survey exports
- **Finance Teams** profiling expense reports for anomalies in seconds
- **Product Teams** analysing feature usage CSVs without writing SQL
- **Students & Researchers** exploring datasets for patterns before formal analysis

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY="your_google_gemini_api_key_here"
```

Get your free API key at [ai.google.dev](https://ai.google.dev).

---

## 📁 Project Structure

```
Augmented-Analytics/
├── app.py                  # Main Streamlit application & agent orchestration
├── agents/
│   ├── cleaner.py          # Data cleaning agent
│   ├── profiler.py         # Statistical profiling agent
│   ├── analyst.py          # Insight generation agent
│   └── visualizer.py       # Chart generation + conversational viz agent
├── requirements.txt        # Python dependencies
├── .env.example            # Environment variable template
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push and open a PR

---

## 📄 License

This project is open source. See the [LICENSE](LICENSE) file for details.

---

## 👤 Author

Built by **[Yahiya Analytics](https://github.com/Yahiya-Analytics)**

*Part of a portfolio of end-to-end data & AI projects. See also: [Legal Lens AI](https://github.com/Yahiya-Analytics/Legal-Lens) · [Agentic AutoML Studio](https://github.com/Yahiya-Analytics/Agentic-AutoML-Studio)*
