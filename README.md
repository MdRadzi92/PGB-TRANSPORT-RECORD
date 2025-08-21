# Transport Record App (Streamlit + Excel) v2

Enhancements:
- **Odometer carry-forward**: When adding new usage, `OdoStart` auto-fills with the vehicle's current odometer.
- **Service alerts**: Dashboard flags vehicles needing service (if Odometer - LastServiceOdo >= threshold).

Threshold can be configured in Excel `Settings` sheet (key=`SERVICE_INTERVAL_KM`, default=10000).