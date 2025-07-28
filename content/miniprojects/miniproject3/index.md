---
title: "Mini Project 3: Predicting copper future price"
date: 2025-07-23
showToc: true
tocOpen: true
weight: 30
showHero: true
heroStyle: background 
summary: This project leverages three exchange markets as well as abudant data on the Internet to build a predictive model for U.S. copper contract prices.
---
<style>
.article-content,
#TableOfContents a {
  color: black;
}

/* Dark mode */
.dark .article-content,
.dark #TableOfContents a {
  color: white;
}
</style>
## Objective: Create an AI model to predict Copper prices
---

## Introduction
The copper futures market involves the buying and selling of standardized contracts that obligate the buyer to purchase and the seller to deliver a specified quantity of copper at a predetermined price on a future date. This market allows traders and investors to speculate on the future price of copper without needing to handle the physical commodity itself. There are three of these copper futures markets in the world: Shanghai, Chicago, and London. People buy and sell these contracts based on their prediction of the future prices of these contracts. The question in this mini project is if we can build a model that can predict the price of copper contracts, specifically the one in the United States.

---

## Methodology and Data
In order to collect the data, we downloaded copper contract prices from three exchanges. Below is the visualization of the data:

![Copper Contract Prices](map.jpg)
The graph shows the fluctuations of the data in relation to time. LME refers to the copper futures market in London. SHFE main refers to the copper futures market in Shanghai. COMEX refers to the copper futures market in Chicago.

![Scatter Plot Matrix](scatter plot.png)
We have a collection of scatter plots that shows the relationship between the trends of the copper futures graph of the ones in Shanghai, Chicago, and London. The labels on the left hand side of the matrix correspond to the y-axis labels of each graph that corresponds to its respective row. The labels on the bottom of the matrix correspond to the x-axis labels of each graph that corresponds to its respective column. From the data, we can tell that the trends of the three different copper futures market are almost exactly the same. The line of best fits for the scatter plots follow a linear shape and can easily fit into a straight line.

![Confusion Matrix](confusion matrix.png)

We then built a Random Forest Model to predict the price of copper contracts. 

---

## Results
add

---

## Discussion
add

---
