# Stock-Forecasting-and-Analysis-Toolkit

This is a modular Python-based project designed for **stock price analysis and forecasting** using machine learning and statistical models.
It automates dependency setup, retrieves **Apple (AAPL)** stock data (2018–2023), and enables **closing price prediction** through tools like **Prophet**, **TensorFlow**, and **Statsmodels** — all within a Colab-friendly workflow.

---

## Features

* **Automated Data Fetching** — Retrieves stock price data using `yfinance`
* **Forecasting Models** — Supports Prophet, ARIMA, and TensorFlow forecasting
* **Environment Setup** — Automatically installs and manages Python dependencies
* **Machine Learning Integration** — Compatible with Scikit-learn and deep learning frameworks
* **Interactive UI (optional)** — Gradio-based web app for demoing predictions
* **Hugging Face Integration** — Easy model sharing and deployment

---

## Tech Stack

* **Python 3.10+**
* **Libraries:** pandas, numpy, matplotlib, statsmodels, scikit-learn, prophet, tensorflow, yfinance, gradio
* **Tools:** Google Colab, Hugging Face Hub

---

## Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/<your-username>/datasynthis.git
cd datasynthis
pip install -r requirements.txt
```

Or run directly in **Google Colab**:

```python
!git clone https://github.com/<your-username>/datasynthis.git
%cd datasynthis
!pip install -q -r requirements.txt
```

---

## Usage

Run the script or notebook to:

1. Fetch historical Apple (AAPL) stock data (2018–2023)
2. Train a forecasting model (Prophet / ARIMA / LSTM)
3. Visualize predicted vs actual stock trends

```bash
python datasynthis__jobtask.py
```

Or in Colab:

```python
%run datasynthis__jobtask.py
```

---

## Example Output

```
Downloading AAPL data (2018–2023)...
Training Prophet model...
Forecast complete — displaying results...
```

A plot of **predicted vs actual closing prices** will appear at the end.

---

## Hugging face Link
```
https://huggingface.co/spaces/tahsintajwar/DataSynthis_Job_task
```

## License

This project is licensed under the **MIT License**.

---

## Author

Developed by **Tanni**
For educational and portfolio use — open to contributions and model extensions!
