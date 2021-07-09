# Project Plan

Pod Members: **Xavier Loera Flores | Carlos Chavez**

## Problem Statement and Description

Many investors see the potential and value of cryptocurrencies but do not own any crypto due to a lack of established trust or knowledge with the cryptocurrency market. We are building a learning platform to introduce new investors to crypto currencies and to build on the knowledge of inexperienced crypto investors.

Our platform will act as a learning platform for new investors to learn about and understand the tokenomics of different cryptocurrencies through a variety of means which include currated lessons/information, a paper trading simulator, and the latest aggregated news relating to cryptocurrencies.

## User Roles and Personas

"Novice": a crypto currency novice aspiring to gain knowledge and experience trading and learning about crypto

"Experienced": a crypto currency enthusiast who wants to track crypto prices and practice trading strategies

Novice:

- Kelly is a student studying economics in San Diego who would like to learn about investing in cryto currencies but isn't old enough to open an account and doesn't know where to start her learning journey. Kelly would like a platform that would help guide her in her crypto learning journey and prepare her to become a crypto investor when she is ready to invest. She spends plenty of her time on her phone while riding the bus and would like to be able to learn on the go with quick easily digestible lessons. 

- Michael a 27 year old experienced index fund and stock investor from New York City who doesn't trust crypto currencies and is weary of all the mixed information about crypo currencies. Michael wants to learn more about the fundamentals of crypto currencies so that he can understand crypto currencies and feel safer about investing his money. He would like to be introduced to different coins with some details on where to find more information on his desktop browser. 

Experienced:

- John is an accountant living in San Francisco, California. He is interested in cryptocurrencies and is experienced with what they are. He spends time trading cryptocurrencies but has taken some recent losses and wants to revise his trading strategies without incurring any actual monetary losses. He mostly trades on a computer and on a frequent basis, almost daily. He is motivated to use this app because he can try his hand at investing into more volatile and risky coins in an effort to research new trading strategies that may help his real investments. 

- Mary is a 25 year old software engineer and experienced crypto investor from Seattle. She wants to discover new coins and gain a larger insight in the tokenomics and history of different coins. Before, she would conduct web searches online but now she wishes there was a consolidated place to gather some key information. Mary wants to be able to search for different coins to learn about its description, price history, available exchanges that support the coin, econonmic indicators, and how each coin compares to another. 

## User Stories

1. As a novice, I want to be able to create an account and login, so that my progress and information can be saved. 
2. As a novice, I want to complete guided lessons, so that I can gain a basic understanding of what crypto currencies are.
3. As a novice, I want to learn about each of the top 10 coins through short understandable lessons, so that I know what it is I am investing in. 
4. As a novice, I want to be able to paper trade crypto currencies, so that I can practice without acquring any risk. 
5. As a novice, I want to be able to see the definitions of different crypto terminology, so that I can understand the information I am reading on charts and news. 
6. As an experienced user, I want to be able to skip the tutorial for coins I am already familar with, so that I can get started with monitoring coins.
7. As an experienced user, I want to be able to view the recent news about certain coins, so that I can understand how it would affect the market.
8. As an experienced user, I want to be able to see what exchanges offer coins I'm interested in, so that I know where I can trade the coin. 
9. As an experienced user, I want to be able to share and read trading strategies with other users, so that I can develop new trading plans.
10. As an experienced user, I want to be able to see a coins popularity on social media, so that I can gauge the amount of interest and properly time my investments. 

## Pages/Screens

List all the pages and screens in the app. Include wireframes for at least 3 of them.

- Wireframe: https://www.figma.com/file/UIiQL2vazLmBZb8x0o9Vo4/Capstone?node-id=0%3A1

- Wireframe Prototype: https://www.figma.com/proto/UIiQL2vazLmBZb8x0o9Vo4/Capstone?node-id=4%3A4&scaling=contain&page-id=0%3A1 

## Data Model

Describe your app's data model using diagrams or tables

## Endpoints

List the API endpoints you will need to implement.

| CRUD | HTTP Verb | Description | User Stories |
| ---- | --------- | ----------- | ------------ |
| Create | POST | Create a new user account | 1 |
| Create | POST | Authenticates user account for sign in | 1 |
| Read | GET | Get's user profile details | 1, 4 |
| Read | GET | See a list of all tutorials | 2, 3, 5 |
| Read | GET | Display single tutorial once clicked | 2, 3, 5 |
| Read | GET | Display personalized dashboard to user  | 4, 6 |
| Read | GET | Display information about a single coin | 4, 7, 8 |
| Create | POST | Purchase coin with paper money | 4 |
| Update | PUT | Update user wallet after purchases | 4 |


***Don't forget to set up your Issues, Milestones, and Project Board!***
