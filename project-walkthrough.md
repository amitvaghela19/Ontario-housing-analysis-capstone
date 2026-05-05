# 📘 Ontario Housing Market Analysis Walkthrough

<p align="center">
  <strong>A step-by-step breakdown of the full project</strong><br>
  <em>From raw housing listings to visual insights across Ontario</em>
</p>

***

## 🌟 Overview

This project is a full exploratory data analysis of housing listings across Ontario. The goal was to understand how prices vary by city, how home features connect with value, and how affordability changes when local income is part of the picture.

Rather than creating charts just for the sake of visuals, the project was designed to tell a story. Each step moves from a simple question to a clearer observation about the housing market.

***

## 🧭 Project Goal

The main idea behind this project was to explore housing in a more realistic way.

Instead of asking only *“which homes are expensive?”*, this project asks:
- Where are homes more expensive on average?
- How much do bedrooms and bathrooms seem to matter?
- Are local income levels keeping up with prices?
- Which cities feel more affordable, and which ones feel more stretched?

***

## 🗃️ Step 1: Understanding the Data

The analysis starts with a housing listings dataset that includes Ontario cities and features such as price, bedroom count, bathroom count, population, and median family income.

This gives the project a strong starting point because it includes both property-level information and city-level context.

### ✅ Observation
The dataset makes it possible to look at housing from more than one angle. Instead of focusing only on price, the analysis can connect price with lifestyle factors, city characteristics, and affordability.

***

## 🧹 Step 2: Preparing the Data

Once the dataset is loaded into Pandas, the structure is reviewed so the important columns can be identified and used for analysis.

At this stage, the project focuses on the core variables that are most useful for answering the main questions: city, price, bedrooms, bathrooms, and median family income.

### ✅ Observation
Good analysis starts by narrowing down the data to the fields that actually matter. Keeping the focus clear helps the story stay simple and readable.

***

## 🏙️ Step 3: Average House Price by City

The first major visual compares average house prices across Ontario cities.

This is one of the most useful places to begin because it quickly shows that Ontario is not one flat housing market. Some cities sit much higher than others, and the spread is wide enough to make city-level analysis essential.

### ✅ Observation
The gap between higher-priced and lower-priced cities is large, which shows how misleading a single provincial average can be.

***

## 🛏️ Step 4: Bedrooms vs Price

The next step explores how bedroom count relates to median house price.

In general, the pattern moves upward: more bedrooms often line up with higher prices. At the same time, some of the extreme categories rise sharply, which likely reflects luxury homes or less common listings rather than the typical market.

### ✅ Observation
This chart shows a useful trend, but it also reminds us to read the edges carefully. Not every category represents the same volume or type of property.

***

## 🛁 Step 5: Bathrooms vs Price

Bathroom count shows a similar pattern to bedrooms. As the number of bathrooms increases, the median listing price also tends to rise.

This is not surprising, but it is still valuable because it confirms that home size and feature count are meaningful parts of pricing.

### ✅ Observation
Bedrooms and bathrooms work as intuitive pricing signals, which makes this part of the project easy for a broad audience to connect with.

***

## 💵 Step 6: Median Family Income vs Price

One of the most interesting visuals in the project compares median family income with housing prices across Ontario cities.

There is some relationship between income and price, but it is far from perfect. Cities with similar income levels can still show noticeably different housing prices, which suggests that income alone does not explain how markets behave.

### ✅ Observation
This is where the project becomes more than a price analysis. It starts to touch affordability, local market pressure, and the limits of using income as a single explanation.

***

## 📊 Step 7: Affordability Ratio

To make the analysis more practical, an affordability ratio is created by comparing home price with median family income.

This adds a much more human layer to the project. A city can have lower absolute prices than Toronto and still feel difficult to afford when local incomes are lower.

### ✅ Observation
This step adds depth to the project because it turns raw price data into something people can relate to more easily.

***

## 🧠 Main Insights

- Ontario housing is highly segmented, with major pricing differences from one city to another.
- Home features like bedrooms and bathrooms generally move in the same direction as price.
- Local income helps explain some pricing patterns, but not all of them.
- Looking at price without income leaves out an important part of the affordability story.
- A clear chart paired with a clear observation is often more powerful than a long technical explanation.

***

## 📌 Notes on Performance Metrics

This version of the project is focused on exploratory analysis, not prediction. That means there are no machine learning evaluation metrics such as RMSE, MAE, or R-squared in the current notebook.

That is completely fine for this kind of project. The strength here comes from how the data is explored, how the visuals are used, and how clearly the findings are explained.

### 🌱 If You Want to Extend It Later
A strong next version could include:
- a correlation heatmap
- summary statistics
- a simple regression model
- feature importance analysis
- residual or error plots

That would make the project even deeper while keeping the current story intact.

***

## 🎨 Why the Visuals Work Well

The charts in this project work because they answer natural questions people already ask about housing:
- Which cities cost more?
- Do larger homes really cost that much more?
- Are local incomes keeping pace?

This makes the project easy to follow even for someone who is not technical.

***

## 🌈 What This Project Shows

This project highlights a mix of technical and communication skills:
- working with real-world data
- organizing and analyzing information with Python
- creating clean charts
- turning findings into a story that feels useful and understandable

***

## 📝 Project Description

Ontario Housing Market Analysis is a data storytelling project built with Python, Pandas, Matplotlib, and Seaborn to explore how home prices vary across Ontario cities. It looks at city-level pricing, the relationship between housing features and value, and the affordability gap between home prices and median family income.

***

## ✨ Closing Thought

What makes a project memorable is not just the code or the charts — it is the clarity of the story behind them. This project works best when it is presented as a real question, explored carefully, and shared in a way that feels thoughtful and human.
