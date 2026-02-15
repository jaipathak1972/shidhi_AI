# Shidhi_AI  

## 🧠 Retail Margin Leak Detector (RMLD)

Retailers mostly track revenue and feel sab theek chal raha hai.  
Sales dashboard green hai, top products move ho rahe hain.  

But real question: **profit kahaan leak ho raha hai?**

Retail Margin Leak Detector (RMLD) is built to uncover hidden margin loss that traditional dashboards miss.

Instead of only tracking sales, RMLD learns what a *healthy margin* should look like for every SKU in every store.  
It studies:

- Historical pricing  
- Supplier costs  
- Discount campaigns  
- Return rates  
- Seasonal patterns  

It builds a baseline profit behavior model.

---

## 🚨 What Happens When Margin Drops?

When margin suddenly falls, the system:

1. Detects the anomaly  
2. Calculates financial impact  
3. Breaks down root cause  
4. Suggests corrective action  

Example:

Expected Margin: 14%  
Actual Margin: 9%  
Estimated Loss: ₹1,40,000  

Root Cause Breakdown:
- 52% discount overlap  
- 31% supplier cost mismatch  
- 17% abnormal returns  

Suggested Action:
- Disable stacked promo  
- Update retail price  
- Audit returns  

Simple. Clear. Actionable.

---

## ⚙️ How It Works

1. Margin Baseline Modeling  
   Learns normal margin pattern per SKU-store combination.

2. Anomaly Detection Engine  
   Flags unusual deviations in profit behavior.

3. Root Cause Attribution  
   Explains *why* margin shifted using data-driven contribution analysis.

4. Action Recommendation Layer  
   Suggests fixes and simulates profit recovery.

---

## 🛠 AWS Stack

- Amazon S3 → Data storage  
- AWS Glue → Data processing  
- Amazon SageMaker → Modeling & anomaly detection  
- AWS Lambda → Automated monitoring  
- Amazon DynamoDB → State management  
- Amazon QuickSight → Executive dashboard  

---

## 🎯 Why This Matters

Small daily margin losses look harmless.  
Monthly, they become serious.  
Quarterly, they become panic.

RMLD turns margin tracking from reactive reporting into proactive intelligence.

Because revenue is vanity.  
Margin is reality.
