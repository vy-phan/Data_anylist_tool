# Dashboard Integration LLM AI

An interactive Streamlit-based dashboard that provides CSV/Excel data visualization, column analysis, and chart creation. The application integrates with the Gemini API for AI-powered data insights, offering analysis recommendations, chart suggestions, and assistance in understanding visualizations.

## Features

### 📂 File Import
- **Supported formats**: CSV,TSV,XLS,XLXS.
- Upload your dataset and instantly view its structure.

### 📊 Column Analysis
- View each column's **unique values** with additional support for rendering images if applicable.

### 🖼️ Chart Creation
- Create dynamic charts with customizable `x` and `y` axes:
  - **Bar Chart**
  - **Line Chart**
  - **Scatter Chart**
  - **Area Chart**

### ➕ Column Calculation
- Create new columns using basic operations: **addition, subtraction, multiplication, division**.
- Changes are dynamically reflected in the dataset.

### 🤖 AI-Powered Insights
- Integrate with **Gemini API** by entering your API key.
- AI provides:
  - Analysis of created charts.
  - Suggestions for new charts.
  - Recommendations for additional columns based on your data.

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dashboard-llm-ai.git
   cd dashboard-llm-ai
