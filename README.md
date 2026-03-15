Football Player Market Value Prediction Dashboard

An interactive Python Dash dashboard to visualize football players’ market values over time, with a 180-day future prediction using Linear Regression.
This project demonstrates data visualization, time-series forecasting, and web-based dashboards.

Note: The dataset (Football_Player_Cleaned.csv) is not included in GitHub for privacy reasons. You must add your own copy in the data/ folder to run the app.

🛠 Features

Interactive dashboard using Dash and Plotly.

Select a player from a dropdown to view historical market values.

Toggle between metrics:

Market Value (€)

Growth %

Predict future market values for the next 180 days using Linear Regression.

Clean, responsive, and interactive visualization.
folder as Football_Player_Cleaned.csv.

📊 How It Works

The dashboard displays historical market values for selected players.

Linear Regression predicts future values for the next 180 days.

Predicted values are shown as a dashed line on the graph.

📄 Requirements

Python 3.8+

Dash

Plotly

Pandas

scikit-learn

Install dependencies using pip install -r requirements.txt.

🔒 Dataset Privacy

The original dataset is private and not pushed to GitHub.

You can replace it with your own dataset using the same format (valuation_date, player_id, name, value_eur, value_growth_pct) for the dashboard to work.
