# 🚗 Dynamic Pricing Engine for Urban Parking Lots

**Capstone Project | Summer Analytics 2025**  
Hosted by **Consulting & Analytics Club × Pathway**

This project simulates an intelligent, real-time dynamic pricing engine for 14 urban parking lots. Prices are adjusted based on live factors such as occupancy, queue length, traffic conditions, special events, vehicle types, and competitor pricing.

---

## 📌 Project Objectives

- Build a data-driven dynamic pricing engine
- Simulate real-time updates using streaming logic
- Visualize pricing evolution through Bokeh
- Incorporate competition, events, and traffic into pricing logic
- Ensure explainable, smooth price transitions

---

## 🧠 Models Implemented

| Model      | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| **Model 1** | Baseline Linear Model adjusting prices based on occupancy rate             |
| **Model 2** | Demand-Based Model considering multiple features (queue, events, traffic)   |
| **Model 3** | Competitive Model adjusting prices using Haversine distance & competitor data |

---

## 🛠️ Tech Stack

- **Python** (Numpy, Pandas)
- **Bokeh** for interactive plots
- **Google Colab** as the execution environment
- **Pathway (conceptual)** for real-time streaming architecture

---

## 🗂 Project Structure

```bash
dynamic-parking-pricing-engine/
│
├── 📄 README.md
├── 📄 requirements.txt
├── 📄 Report.pdf
├── 📄 problem_statement.pdf
├── 📊 dataset.csv
│
├── 📁 notebook/
│   └── code.ipynb
│
├── 📁 visuals/
│   └── architectural_flow.drawio.png
