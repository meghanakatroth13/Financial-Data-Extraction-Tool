# Financial-Data-Extraction-Tool
# Financial-Data-Extraction-tool-in-python
Financial Data Extraction tool in python
***

# 💸 Financial Data Extraction Tool in Python

Extract key financial metrics from unstructured news articles—instantly and accurately—using modern AI (OpenAI GPT-3.5), prompt engineering, and Streamlit!

***

## 🚀 What Does It Do?

- **Transforms messy news text** into a clean financial table  
- Extracts essential metrics: **Company Name, Stock Symbol, Revenue, Net Income, EPS**
- Presents results in a simple, interactive web app  
- Makes financial analysis fast, reliable, and scalable[2][3][1]

***

## 🖥️ Live Demo / Preview

Just paste a financial news article and hit “Extract”—see your data appear in a structured, tabular format.

***

## 🎯 Features

- **AI-powered NLP**: Uses OpenAI GPT-3.5 for advanced information extraction[3][1]
- **Prompt Engineering**: Ensures precise, structured JSON outputs
- **Streamlit Frontend**: User-friendly, responsive interface
- **Instant Results**: No need for manual copy-pasting or parsing
- **Valid JSON & Pandas Table**: Guaranteed clean, parsable results

***

## 🛠️ Tech Stack

| Technology   | Role                                      |
|--------------|-------------------------------------------|
| **Python**   | Scripting + Data Handling                 |
| **OpenAI GPT-3.5** | Language Model for Extraction      |
| **Streamlit**| Interactive Web UI                        |
| **Pandas**   | Tabular Data Manipulation                 |

***

## 🚦 Quick Start

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/financial-data-extraction-tool.git
   cd financial-data-extraction-tool
   ```

2. **Install dependencies**  
   ```bash
   pip install streamlit openai pandas
   ```

3. **Set your OpenAI API key**  
   Edit `helper.py` to paste your key (`openai.api_key = "YOUR_KEY_HERE"`).  
   *[Keep your key secure; never share it publicly.]*

4. **Launch the app**  
   ```bash
   streamlit run main.py
   ```

***

## 📝 How It Works

- Paste a financial news article or earnings report into the text box.
- Click `Extract` to trigger AI-powered parsing.
- Extracted items:  
  - **Company Name**  
  - **Stock Symbol**  
  - **Revenue**  
  - **Net Income**  
  - **Earnings Per Share (EPS)**
- Data appears instantly in a table—ready for analysis or export.[1][2][3]

***

## 🧩 Example Input/Output

**Input (article):**
```
Tesla's earnings this quarter exceeded expectations, posting a profit of $4.5 billion and revenue of $30 billion. EPS came in at $2.3.
```

**Output Table:**

| Measure        | Value          |
|----------------|---------------|
| Company Name   | Tesla         |
| Stock Symbol   | TSLA          |
| Revenue        | $30 billion   |
| Net Income     | $4.5 billion  |
| EPS            | $2.3          |

***

## 💡 Customization Ideas

- Add support for more metrics (Operating Margin, ROI, etc.)
- Export results to CSV or Excel
- Batch process multiple articles
- Integrate with financial APIs or dashboards

***

