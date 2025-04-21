# LCA Bot – Production Version 🌱

This is a production-ready ISO-compliant Life Cycle Assessment (LCA) report generator powered by OpenAI and web-scraping.

## 🔧 Features
- Generate DOCX LCA reports with GPT-3.5 or GPT-4
- Upload CSVs or auto-generate inventory data
- Web scraping for product-specific context
- Interactive Streamlit UI
- Visualizations (bar charts, impact plots)
- Downloadable reports (DOCX)

## 🚀 Run Locally

1. Install requirements:
```
pip install -r requirements.txt
```

2. Set your API key:
```
export OPENAI_API_KEY="sk-..."
```

3. Launch the app:
```
streamlit run lca_bot_production.py
```

## 🌐 Deploy on Streamlit Cloud

Add this to your Secrets:
```toml
OPENAI_API_KEY = "sk-..."
```

Enjoy!
