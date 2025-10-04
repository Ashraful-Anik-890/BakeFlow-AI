# BakeFlow AI

BakeFlow AI is a smart, interactive web application designed to help artisanal bakeries predict daily product demand, reduce food waste, and maximize sales. It leverages historical sales data, weather forecasts, and special event information to generate accurate, actionable predictions for bakery owners.

## Features

- **Three-Day Weather Forecast:**
  - Simulates local weather to factor into demand predictions.
- **CSV Sales Data Upload:**
  - Upload your historical sales data (CSV format: `Date, Item_Name, Units_Sold`).
  - Example provided and sample CSV download available.
- **Prediction Engine:**
  - Choose from multiple algorithms: Weighted Average, Simple Moving Average, or Day-of-Week Trend.
  - Adjust for weather and promotions/special events.
  - Get a clear, animated prediction for tomorrow’s demand.
- **Sales Visualization:**
  - Bar chart of the last 7 days’ sales for the selected item, plus tomorrow’s prediction.
  - Pie chart showing overall sales distribution by item.
- **Promotion Blurb Generator:**
  - (Requires API key) Instantly generate a social media blurb for your predicted best-seller.
- **Ingredient Substitution Suggestor:**
  - (Requires API key) Get smart, context-aware ingredient swaps for baking.
- **Contact Section:**
  - Developer contact and project purpose.

## How It Works

1. **Upload Sales Data:**
   - Click "Upload CSV" and select your sales file.
   - The app parses your data and enables item selection.
2. **Set Prediction Details:**
   - Choose the item, prediction algorithm, expected weather, and if a promotion is planned.
   - The app predicts tomorrow’s demand and explains the reasoning.
3. **Visualize Trends:**
   - View recent sales and overall item distribution.
4. **Generate Blurbs & Suggestions:**
   - Use the blurb generator and ingredient suggestor (API key required for Google Gemini).

## CSV Format Example

```
Date,Item_Name,Units_Sold
2025-07-15,Sourdough Loaf,100
2025-07-15,Croissant,150
2025-07-16,Sourdough Loaf,95
...
```

## Technologies Used
- HTML5, CSS (Tailwind), JavaScript (Vanilla)
- Canvas for background and charts
- Google Gemini API (for blurb and suggestion features; API key required)

## Developer
**MD. Ashraful Al Amin**  
Email: [ashrafulanik08@gmail.com](mailto:ashrafulanik08@gmail.com)

---
© 2026 BakeFlow AI. All rights reserved.
