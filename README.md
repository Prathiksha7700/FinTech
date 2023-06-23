# EcoInvest Financial Dashboard with Plotly Dash

## Introduction
This is an educational project for a fictional startup called EcoInvest. It is a stock trading app for beginner's, aimed at students that aids trading of standard sustainable companies. The MVP developed is a GUI for a financial dashboard in the app. The main UX feature is the great ease of use. There is vast information available to support decision making as well as easy to read visualizations to help user understand and predict stock market activity.

## Plotly Dash
The main programming language and framework used is Plotly Dash in Python. It is a powerful tool for data science visualizations and Python comes with many helpful libraries. The Python version used is Python 3.11.2. The Data sourced is from Yahoo Finance using the APIs yfinance and yahooquery.  

## The App
The main feature and UX of the dashboard is the great ease of use and navigation between company stock market data and business performance data. It is aimed at beginner's stock traders, specifically for sustainable stocks aimed at increasing investment in the UN's SDGs.

The idea is to create a webpage with 3 tabs with the below layout. The tabs have the following functions:

Tab1 : Get stock market information on top companies from which user has bought stocks, in terms of share price. If new, these will just show the top 3 stocks in general. This page is to include focussed details about the securities'. Including the price, the volume, moving average signals and stochastic signals. All these terms and indicators will be both displayed and described to get a meaningful understanding of the security. It is an overview of current stocks held by user, to monitor and compare the activities. The user can scroll through the top stocks using a dropdown menu, which will trigger a callback to adjust the information displayed accordingly.

Tab2: The second tab is a financial assistant board for the businesses themselves. This will illustrate the main financials of the company selected and depict the recent evolution of the company's performance as these are also important indicators of the stock price momentum. These figures are also to be explained on the bottom of the page to support the users interpreting them. Again, the sought company can be navigated through a dropdown menu.

Tab3: The final tab serves as a data query functionality. It allows the user to search up any stocks, whether sustainable or not and whether they invest in them or not (in the case that they are sustainable). Here the trader can use a input search box to access the data. The graphs displayed on this page are the same as those on tab1.

## Deployment
The GUI is to be deployed by sharing it to a given server using Dash Enterprise Deployment software. After installing this product, the Dash Enterprise platform comes with various tools for a complete Analytical App Stack. Using its authentication middleware, the end users can be connected to the app with identity verification. Furthermore, active license seats are required for users to make, access, and manage the apps.

## DEMO
