# ⚖️ BillSync AI — Multi-Agent Billing Reconciliation

A multi-agent AI application that reconciles invoices against payment records using 4 specialised Claude AI agents.

## 🤖 The 4 Agents

| Agent | Role |
|---|---|
| **Data Analyst** | Reads and validates uploaded CSV files |
| **Matching Agent** | Pairs each invoice to its payment |
| **Auditor** | Flags risks, duplicates, and anomalies |
| **Report Writer** | Generates the executive summary |

## 🚀 Running the App

### On Streamlit Cloud (recommended)
1. Fork this repo to your GitHub account
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub repo
4. Deploy — no setup needed

### Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🔑 API Key
You will need an Anthropic API key from [console.anthropic.com](https://console.anthropic.com).
Enter it in the sidebar when the app loads. It is never stored.

## 📁 Sample Data
Use the provided `invoices.csv` and `payments.csv` files to test the app.

## 🛠 Built With
- [Streamlit](https://streamlit.io) — web UI
- [Anthropic Claude](https://anthropic.com) — AI agents
- [Pandas](https://pandas.pydata.org) — data handling
