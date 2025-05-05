# Customer Churn Prediction 🚨

This project predicts customer churn for a telecom company 60 days in advance, using machine learning and risk segmentation. It helps reduce revenue loss by identifying high-risk customers and enabling targeted retention efforts.

---

## 📊 Summary

- **Data**: 20,000+ customers (CRM, billing, usage logs)
- **Model**: Logistic Regression (`AUC = 0.8264`)
- **Features**: 45 engineered fields (usage, payments, complaints)
- **Churn Rate**: ~26%
- **High-risk customers identified**: 520

---

## 🧠 Risk Segmentation

| Risk Category | Count | Churn Rate (%) |
|---------------|-------|----------------|
| Low           | 635   | 5.67           |
| Medium        | 254   | 28.34          |
| High          | 281   | 37.36          |
| Very High     | 239   | 67.36          |

📊 See charts:  
- `risk_category_analysis.png`  
- `churn_prediction_dashboard.png`

---

## 💰 Business Impact

- **Retention Program Cost**: $52,000  
- **Estimated Retained Customers**: 208  
- **Revenue Saved**: $249,600  
- **Net Profit**: 💰 $197,600

---

## 🧪 Model Performance

- **AUC**: 0.8264  
- **Accuracy**: ~73%  
- **Precision (churn)**: ~51%  
- **Recall (churn)**: ~71%  
- **F1 Score**: ~60%

Confusion Matrix:
       Predicted
       0    1
Actual 0 | 781 254
Actual 1 | 108 266