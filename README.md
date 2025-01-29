# 📊 Power BI Sales Analysis Dashboard

## 📌 Overview  
This Power BI dashboard provides insights into **sales performance, product demand, and profitability**. The key metrics analyzed include:  
- **Most Ordered Product** 🏆  
- **Total Sales** 💰  
- **Total Buy Price** 📉  
- **Total Profit** 📊  

## 📈 Key Metrics & Analysis  

### 🔹 Most Ordered Product  
Using **DAX calculations**, the dashboard identifies the product with the **highest total quantity ordered**.  

### 🔹 Total Sales Calculation  
Total Sales is calculated as the **sum of all sales transactions** from the `Order Details` table:  

```DAX
TotalSales = SUM('Order Details'[Sales])
```

### 🔹 Total Buy Price Calculation  
Total Buy Price is calculated as:  

```DAX
TotalBuyPrice = SUM('Order Details'[Buy Price])
```

### 🔹 Total Profit Calculation  
Total Profit is calculated as:  

```DAX
TotalProfit = [TotalSales] - [TotalBuyPrice]
```

## 📊 Dashboard Features  
✔ **Interactive visualizations** for product sales trends 📊  
✔ **Top-selling product identification** using DAX 🏅  
✔ **Profitability insights** to track business performance 📈  

## 🚀 How to Use  

1. Open the Power BI file (`MY_power_bi.pbix`) in **Power BI Desktop**.  
2. **Interact with the dashboard** to analyze different products and sales performance.  
3. Use **slicers** to filter by **date, product category, or region**.  

## 🛠️ Technologies Used  
- **Power BI** for visualization  
- **DAX** for calculations  
- **SQL** (if applicable for data processing)  

## 📥 Installation & Setup  

1. Download and **install Power BI Desktop**.  
2. Open the provided `.pbix` file.  
3. **Refresh the data** if needed.  

## 📢 Feedback & Contributions  
Feel free to **raise issues** or **suggest improvements**! 🚀

## 📬 Contact

For questions or feedback, feel free to contact:

- **Author:** Naim
- **Email:** naimurrashid1105@gmail.com ✉️
- **GitHub:** [Naim007-cooder](https://github.com/Naim007-cooder)

Thank you for exploring this project! Happy analyzing! 🎉
