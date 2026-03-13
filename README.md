# Product-Portfolio-Risk-Service-Level-Modelling
Product Portfolio Risk &amp; Service Level Modelling(Tonin Kaipada Thomas, M.Sc Data Science)

1️⃣Tools & Technologies-
1. Python (Pandas, NumPy)
2. Statistical Modelling (CV, Z-score)
3. Power BI (dashboard & portfolio visualization)
4. Matplotlib (exploratory visualization)

2️⃣Business Problem -
1. Modern product portfolios often suffer from:
2. Revenue concentration risk
3. Demand volatility
4. Inefficient service level allocation
5. Excess safety stock or stockouts

The objective of this project was to design a structured analytical framework to:
1. Identify revenue-critical products
2. Quantify demand volatility
3. Segment the portfolio by risk and contribution
4. Translate segmentation into differentiated service level policies

3️⃣ Analytical Framework-
This project follows a 3-layer analytical structure:

Layer 1 — Revenue Segmentation (ABC Analysis)
* Calculated total revenue per product
* Computed contribution percentage
* Performed Pareto-based ABC classification

Layer 2 — Demand Volatility Modelling
* Calculated mean monthly demand
* Calculated standard deviation
* Computed Coefficient of Variation (CV)
* Classified products into stability tiers

Layer 3 — Risk–Revenue Portfolio Positioning
* Built a Risk–Revenue matrix
* Mapped revenue contribution vs demand volatility
* Identified high-risk revenue dependencies

4️⃣ Service Level Policy Design-
* To translate analysis into operational policy:
* Assigned differentiated service levels by ABC class
* Converted service levels to Z-scores
* Calculated Safety Stock using:
Safety Stock = Z × σ
* Estimated Reorder Points

This bridges analytics and inventory decision-making.


[Portfolio risk dashboard](images/portfolio_risk_dashboard.png)

5️⃣ Key Insights-
* 77.8% of total revenue is driven by A-class products
* Portfolio average CV indicates moderate-to-high demand variability
* Revenue concentration combined with volatility exposes structural risk
* Differentiated service level design reduces overstock in low-impact products
* Volatile products require significantly higher safety stock buffers

6️⃣ Operational Implications-
1. A-class products require priority forecasting and higher protection
2. C-class volatile products should follow leaner inventory policies
3. Volatility-adjusted service level design improves capital efficiency
4. Portfolio segmentation enables risk-aware resource allocation

8️⃣ Conclusion

This project demonstrates how descriptive analytics (ABC & CV) can be extended into prescriptive decision modelling through structured service level policy design.

It showcases:
* Risk-based segmentation
* Revenue concentration analysis
* Volatility quantification
* Inventory decision translation
