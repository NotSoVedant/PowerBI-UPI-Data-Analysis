# 💸 Power BI – UPI Data Analysis

This Power BI project analyzes Unified Payments Interface (UPI) transaction data to uncover key financial trends and user behavior patterns. It demonstrates data transformation, interactive dashboard design, and storytelling using Power BI bookmarks and visuals.

---

## 📁 Dataset

The dataset (`UPI_Transactions.xlsx`) contains:
- Transaction Date
- Amount & Balance
- Transaction Channel
- Age Group (derived)
- Month & Year (derived)

---

## 🔧 Tools Used

- Microsoft Power BI Desktop
- Microsoft Excel
- Power BI Service (for cloud deployment)

---

## 🚀 Key Features

### 🧹 Data Preparation
- Imported Excel data into Power BI
- Performed **data profiling** to ensure data quality
- Added calculated columns:
  - `Age Group` using nested `IF` conditions
  - `Page` for navigation purposes
  - `Month` and `Year` from transaction dates

### 📊 Visualizations
- **Line Charts** to show trends in UPI transaction amount and balance over time
- **Column Charts** for categorical comparisons
- **Matrix Visual** for segment-based tabular insights
- **Conditional Formatting** to highlight significant data points

### 🧩 Interactivity
- Multiple **slicers** for age group, channel, and date range
- Slicers were **formatted** and **positioned** for clean UI
- **Slicer syncing** was applied across all pages

### 🔁 Bookmarks & Navigation
- Created **bookmarks** to switch between:
  - **4 Insight Views**: 
    - Page_1.1: Line Chart – Transaction Amount
    - Page_1.2: Line Chart – Remaining Balance
    - Page_1.3: Column Chart – Transaction Amount
    - Page_1.4: Column Chart – Remaining Balance
  - **Page_2**: Detailed Transaction and Balance View
- Added buttons for intuitive **insight switching**

### ☁️ Deployment
- Published to **Power BI Service** for web access

---

## 📷 Report Snapshots

| Insight View | Screenshot |
|--------------|------------|
| 📈 Transaction Amount (Line Chart) | ![Page 1.1](./images/Page_1.1.png) |
| 📈 Remaining Balance (Line Chart) | ![Page 1.2](./images/Page_1.2.png) |
| 📊 Transaction Amount (Column Chart) | ![Page 1.3](./images/Page_1.3.png) |
| 📊 Remaining Balance (Column Chart) | ![Page 1.4](./images/Page_1.4.png) |
| 📄 Transaction Details | ![Page 2](./images/Page_2.png) |

---

## 🎯 Business Impact

This project helps financial analysts and fintech stakeholders:
- Monitor UPI transaction trends over time
- Compare age-group-based transaction patterns
- Understand remaining balance behavior
- Explore insights interactively with smooth navigation and dynamic filtering

---

## 📁 Files Included

- `POWER_BI_PROJECT_3.pbix` – Final Power BI dashboard
- `UPI_Transactions.xlsx` – Source dataset
- `/images` – Dashboard snapshots

---

## 📫 Author

**Vedant Pritesh Bhadiyadra**  
📧 vedantjpb2004@gmail.com  
🔗 [GitHub](https://github.com/NotSoVedant)  
🔗 [LinkedIn](https://www.linkedin.com/in/vedant-bhadiyadra-174865297)

---

## 🙏 Credits & Learning Inspiration

This project was created as part of my learning journey through the excellent Udemy course:

📘 **[The Complete Data Analyst Bootcamp](https://www.udemy.com/course/the-data-analyst-course-complete-data-analyst-bootcamp/)**  
🎓 Instructor: Krish Naik

Special thanks to Krish Naik for clear explanations and hands-on projects that helped shape my understanding of real-world data analysis.

This Power BI dashboard is built independently based on concepts learned in the course and showcases my practical application of data analysis skills.
