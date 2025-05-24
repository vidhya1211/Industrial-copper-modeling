🧪 Industrial Copper Modeling 
This project focuses on modeling industrial copper data to predict two key outcomes using machine learning:
•	Selling Price Category: Categorizing the price of copper into Low, Medium, or High.
•	Copper Status: Determining whether the copper status win or loss.
We use the Decision Tree Classifier from scikit-learn to build interpretable models for classification.

📌 Problem Statement
Copper is a crucial industrial metal, and pricing or sales status can be influenced by various factors such as physical properties, production costs, and market demand. The goal is to use historical data to train models that can predict:
•	The price category of copper (to assist in strategic pricing).
•	The status of copper (to estimate demand and movement).

📊 Dataset Features
Key features used in modeling include:
•	grade: Grade/type of copper
•	thickness: Thickness of the copper sheet
•	width: Width of the copper sheet
•	production_cost: Cost incurred during production
•	market_demand: Demand indicator
•	selling_price_category: Target – categorized price (Low / Medium / High)
•	status: Target – whether Sold or Not Sold

🧠 Machine Learning Model
•	Algorithm: Decision Tree Classifier
•	Library: Scikit-learn
•	Process:
o	Data loading and cleaning
o	Feature selection
o	Train-test split
o	Model training
o	Prediction and evaluation using accuracy, precision, recall, and F1 score

✅ Results
•	The Decision Tree provided clear and interpretable logic for classification.
•	Feature importance analysis showed that market demand and production cost were significant in influencing both price and status.
•	Accuracy scores varied by target but showed promising predictive ability.

🛠️ Tools Used
•	Python
•	pandas
•	scikit-learn
•	matplotlib (for visualization)
•	Streamlit
🚀 Future Enhancements
•	Apply ensemble methods like Random Forest or XGBoost for improved accuracy.
•	Visualize the tree structure and feature importance.
