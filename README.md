# 📊 Fin Scope Planner  
**Personal Investment Planning Tool**

**Fin Scope Planner** is a personal tool designed to quickly calculate a recommended investment percentage based on your income and automatically distribute the investment amount across selected asset categories.  
The project was created for personal use but can be helpful for anyone who wants a structured approach to investing.

---

## ✨ Features

### 📈 Dynamic Investment Percentage Calculation  
Automatically suggests an optimal investment percentage depending on your income.

### 🔢 Linear Interpolation  
Uses interpolation to calculate the percentage between:  
- **MIN% / MAX%**  
- **MIN_SALARY / MAX_SALARY**

### 💰 Automatic Investment Amount Calculation  
After entering your income, the tool instantly shows how much you should invest.

### ⚙️ Custom Allocation by Asset Categories  
You can define your own distribution ratios across categories:  
- **Safe Assets**  
- **ETF / Stocks**  
- **Cryptocurrency**  
- **Education**

### 🥧 Pie Chart Visualization  
Displays the final allocation in a clean **pie chart**.

### 📋 "Copy Result" Button  
Allows you to quickly copy the full investment breakdown.

### 🌚 Dark Mode  
A comfortable dark interface for easy use anytime.

---

## 🧠 Interpolation Formula

```js
ratio = (salary - MIN_SALARY) / (MAX_SALARY - MIN_SALARY)
percent = MIN_PERCENT - ratio * (MIN_PERCENT - MAX_PERCENT)
```

### 🚀 Project Setup
```bash
git clone https://github.com/your-user/fin-scope-planner.git
cd fin-scope-planner
npm install
npm run dev
```


### 📜 License
This project is distributed under the MIT License, allowing free use, modification, and distribution.
