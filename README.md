# 🚗 Automobile Sales Analysis & Dashboard
تحليل مبيعات السيارات ولوحة متابعة تفاعلية

Python Dash License

🇬🇧 English & 🇸🇦 Arabic Version

---

📄 **Project Overview / نظرة عامة عن المشروع**  
This repository contains a complete analysis of **USA automobile sales data (2018–2024)**, including static and interactive visualizations.  
The goal is to explore trends, the impact of recession, GDP changes, seasonality, advertising expenditure, and unemployment on vehicle sales.  
يحتوي هذا المستودع على تحليل كامل لبيانات مبيعات السيارات في الولايات المتحدة بين 2018 و2024، يشمل الرسوم البيانية الثابتة والتفاعلية.  
الهدف هو استكشاف الاتجاهات، تأثير الركود، تغيرات الناتج المحلي الإجمالي، الموسمية، الإنفاق الإعلاني، ونسبة البطالة على مبيعات المركبات.

---

📂 **Dataset / مجموعة البيانات**  
The dataset is sourced from **Kaggle**: [USA Car Sales Dataset (2018–2024)](https://www.kaggle.com/datasets/anjaliprajapati307/usa-car-sales-dataset-2018-2024)  
تم أخذ البيانات من **Kaggle**: [مجموعة بيانات مبيعات السيارات في الولايات المتحدة 2018–2024](https://www.kaggle.com/datasets/anjaliprajapati307/usa-car-sales-dataset-2018-2024)

**Key columns / الأعمدة الرئيسية:**
- `Year` — Year of sale / سنة المبيعات  
- `Vehicle_Type` — Type of vehicle (Sedan, SUV, Truck) / نوع المركبة (سيدان، SUV، شاحنة)  
- `Sales` — Sales volume / حجم المبيعات  
- `Recession` — Indicates recession period / يوضح فترة الركود  
- `Advertising_Expenditure` — Ad spend data (per vehicle type and period) / بيانات الإنفاق الإعلاني لكل نوع مركبة والفترة  

---

📊 **Data Visualizations / الرسوم البيانية**  
**Python libraries used / المكتبات المستخدمة:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `dash`

Visualizations include / تشمل الرسوم:  

1. **Line Chart – Total Automobile Sales per Year**  
   مخطط خطي – إجمالي المبيعات السنوية للسيارات  
   ![Automobile Sales per Year](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/Automobile%20Sales%20per%20Year.png?raw=true)

2. **Line Chart – Sales Trend per Vehicle Type**  
   مخطط خطي – مقارنة اتجاهات المبيعات لكل نوع مركبة  
   ![Sales Trend per Vehicle Type](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/Sales%20Trend%20per%20Vehicle%20Type.png?raw=true)

3. **Line Chart – Sales Trend per Vehicle Type (Recession vs Non-Recession)**  
   مخطط خطي – مقارنة المبيعات لكل نوع مركبة خلال فترات الركود وغير الركود  
   ![(Recession vs Non-Recession)](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/(Recession%20vs%20Non-Recession).png?raw=true)

4. **Side-by-Side Line Plots – GDP Analysis**  
   مخططات خطية جنبًا إلى جنب – تحليل الناتج المحلي الإجمالي خلال الركود وغير الركود  
   ![GDP Analysis](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/GDP.png?raw=true)

5. **Bubble Plot – Seasonality Impact on Sales**  
   مخطط فقاعات – تأثير الموسمية على المبيعات  
   ![Seasonality Impact](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/Seasonality%20Impact%20on%20Automobile%20Sales.png?raw=true)

6. **Pie Charts – Advertising Expenditure Analysis**  
   مخططات دائرية – تحليل الإنفاق الإعلاني حسب الفترة ونوع المركبة  
   ![Advertising Expenditure](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/Correlation%20Average%20Vehicle%20Price%20vs%20Sales%20During%20Recession.png?raw=true)

7. **Line Plot – Effect of Unemployment Rate on Vehicle Sales**  
   مخطط خطي – تأثير معدل البطالة على مبيعات المركبات  
   ![Unemployment Rate Effect](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/Effect%20of%20Unemployment%20Rate%20on%20Vehicle%20Sales.png?raw=true)

9.  **Sedan Sales Over Years - Interactive Dashboard **   
   لوحة متابعة تفاعلية لمبيعات سيارات السيدان على مر السنين 
   ![Interactive Dashboard](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/Sedan.png?raw=true)

10. **Truck Sales Over Years - Interactive Dashboard **  
   لوحة متابعة تفاعلية لمبيعات الشاحنات على مر السنين 
   ![Interactive Dashboard](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/Truck.png?raw=true)

11. **SUV Sales Over Years - Interactive Dashboard **  
   لوحة متابعة تفاعلية لمبيعات سيارات الدفع الرباعي على مر السنين 
   ![Interactive Dashboard](https://github.com/Raghad-ALmarshadi/USA-Car-Sales-2018-2024-Analysis/blob/main/ScreenShot%20/SUV.png?raw=true)

---

🖥️ **Interactive Dashboard / لوحة متابعة تفاعلية**  
**Features / الميزات:**  
- Dropdown for selecting Vehicle Type / قائمة منسدلة لاختيار نوع المركبة  
- Dynamic line chart showing sales trend for selected vehicle / مخطط خطي ديناميكي يعرض اتجاه المبيعات لنوع المركبة المختار  
- Real-time updates when selection changes / تحديثات فورية عند تغيير الاختيار

---

🚀 **How to Run Locally / طريقة التشغيل محليًا**  

1. Clone the repository / استنساخ المستودع:  
```bash
git clone https://github.com/yourusername/automobile-sales-dashboard.git
```

2.Install required libraries / تثبيت المكتبات المطلوبة:
```bash
pip install pandas numpy matplotlib seaborn plotly dash
```
3.Run the notebook for static visualizations / تشغيل الـ Jupyter Notebook للمخططات الثابتة:
```bash
jupyter notebook analysis.ipynb
```
4.Launch the interactive dashboard / تشغيل لوحة المتابعة التفاعلية:
```bash
python app.py
```
5.Open the browser at / فتح المتصفح على الرابط:
```bash
http://127.0.0.1:8050/
```
6.Interact with the dashboard / التفاعل مع لوحة المتابعة:

- Use the Vehicle Type dropdown to select a vehicle / استخدمي قائمة المنسدلة لاختيار نوع المركبة

- Charts will update automatically based on selection / ستتحدث المخططات تلقائيًا حسب الاختيار

📝 Project Structure
graphql
Copy code
├── data/                  # CSV dataset from Kaggle
├── visuals/               # Exported static charts
├── app.py                 # Dash interactive dashboard
├── analysis.ipynb         # Jupyter Notebook with analysis
└── README.md              # Project documentation
📈 License
Open-source for educational purposes / مفتوح المصدر لأغراض تعليمية

✨ Author / المؤلف: Raghad Almarshadi
✨ GitHub: https://github.com/Raghad-ALmarshadi
✨ LinkedIn: https://www.linkedin.com/in/raghad-almarshadi-99b5bb25b/


