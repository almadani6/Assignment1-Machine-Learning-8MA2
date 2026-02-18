# 📁 Dataset Description - Assignment 1, Machine Learning-8MA2.

## Dataset Name
`car-sales-saudia.csv`

## 🧠 Context
This dataset contains real-life used car listings. Each row represents one car advertisement with technical and market-related information.

## Columns
- `Brand`: Car type (BMW, Audi, Toyota, etc....)
- `Price`: Car selling price 
- `Body`: Body type (sedan, hatch, crossover, etc....)
- `Mileage`: Distance driven in thousand km
- `EngineV`: Engine capacity
- `Engine Type`: engine Fuel category (Petrol, Diesel, Gas, Other)
- `Registration`: Registration status (`yes` or `no`)
- `Year`: Manufacturing year
- `Model`: Car model

## ⚠️ Data Quality Notes
- Some rows include missing or non-numeric values in `Price` for instance `NA` so we must cleaning .
- Data types need conversion for numeric analysis (`Price`, `Mileage`, `EngineV`, `Year`).
- Outliers exist (very high prices and unusual mileage), which is expected in real market data.

## 🎯 EDA Goal
The goal is to explore patterns that affect car prices and prepare data for future machine learning (price prediction).
