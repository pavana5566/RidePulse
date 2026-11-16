# RidePulse

RidePulse is a premium smart mobility analytics platform for public transport ridership monitoring, forecasting, and operational optimization.

## Demo credentials

This demo authentication is intentionally simple and designed for hackathon use only. It is not production-secure authentication and does not store passwords in plain text.

- Email: demo@ridepulse.ai
- Password: ridepulse-demo

## Local setup

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
streamlit run app.py
```

## Features

- Premium landing page and startup-style UX
- Demo login flow with Streamlit session state
- Smart dashboard with ridership KPIs and interactive Plotly charts
- Demand forecasting and schedule optimization logic
- Responsive layout for desktop and mobile screens

## Notes

- The app uses synthetic ridership data for demonstration and prediction purposes.
- The login flow is demo-only and should not be used for real account security.
- The visual design is intentionally built to feel like a modern future mobility product for a college hackathon.
