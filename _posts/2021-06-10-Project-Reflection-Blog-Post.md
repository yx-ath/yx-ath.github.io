---
layout: post
title: Project Reflection Blog Post
---

> In this blog post, I'll write a reflection on the [class project](https://github.com/guanzhangszhao/YoungNRich) I've done with team *YongNRich*, as well as my project contribution part.

## Project Introduction Link

The project works intend to create optimized portfolio with high returns that could be considered as an reference to common investors. Here is the link to the project: [Portfolio Optimization with Stock Volatility](https://github.com/guanzhangszhao/YoungNRich)

## Project Reflection

##### 1. Project Achievements

-  Based on the Fama-French three factor Model, we analyzed and predict the stock performance, retrieving alpha signal, and find the potentially nice combinations of resource (compared to the other combinations from the resources we have) that retrieves stock volatility with a low mean squared error, performed a test on the short-term stock market

- Doing a web scrape from tweets, reddits, as well as tipranks is the sub-effect created by this project. Could be further used and written as a package for user's further usage.

- Retrieve stocks from Yahoo Finance datasets

- Apply tensorflow neural network models as sentiment analysis to predict stock volatility and therefore further predicts stock returns

- Combining predicted returns and alpha signals, finally constructed optimized portfolio as expected.

##### 2. How the Project is Exciting (Prouds)

- By testing on different methods, we actually reduced the mse to a level that we are expected to see, which is a nice prediction method in our project for constructing optimized portfolio with returns. Using twitter as stock volatility predictions let us generally predicts daily patterns from historical webpages, and is thus a highlight point in our project.

- By testing a lot of different models with different inputs, we are able to find that the best match for predicting stock returns is with the sentiment analysis combined with twitter

##### 3. Potential Improvements

- Higher Computing Power: due to the limitation of computing power in our project. We only choose to include 20,000 characters from daily retrieved twitter, otherwise it is really hard for the project running process. Therefore, the predictions won't be that accurate as expected. We expect the accuracy to be better with a higher computing power.

- Public Information Restriction of Market: due to the limitation of resource, for the trading information, we are only able to access from Tiprank, which only gives weekly trading data in a constrained time period. As proved in the [Volatility Sentiment Analysis](https://github.com/guanzhangszhao/YoungNRich/commit/9240c4e4af6b67d76f735bb807d6d1733cdb19bf), such weekly information, due to the long time period comparing to daily trading, actually constraints the model and makes the model more unstable. Therefore, we probably need to have access to more short-term information related to daily prediction, such as trading and stock information.

##### 4. Way to Proposal

- Compared to our project proposal, we are using less information in general compared to the original plan of putting all reddit, twitter and tiprank as sources for our sentiment analysis. We also shown that using twitter only is the best prediction method to be considered

##### 5. Learning from the Experience

- In my experience of this project,I am now able to do [sentiment analysis](https://github.com/guanzhangszhao/YoungNRich/commit/9240c4e4af6b67d76f735bb807d6d1733cdb19bf) and to compare different results in the model selection process in general
- I've learned in general how to retrieve data from different API ranks and selecting useful data and converting them into dataframes for further analysis. I think this is really important for my further researches
- Althoguh did not partially shown in the final version of this project, when we did not discover API for tiprank yet, I tried to convert the existing Java package into python for usage. I think this experience is also important for me, as many packages contains either only python version or Java version. Converting those in Java language to JavaScript and further convert .js into python is a really interesting experience of me, and I value this experience for further converting packages between different programming languages

##### 6. Effect to Further Study

- I learned the fact that quant researches are sometimes constrained by the computing power and resource limitation, instead of lack of knowledge and skills to do improvement. I think this would influence my future study in the field of quantitative research
- As I planned getting into the field of Financial Engineering, this project provides me a complete experience on analyzing market trends, specifically stock returns, as well as constructing optimized portfolio in a relatively professional way. Having this complete experience, I think my skills in quantitative research improves a lot, which is important for my future research and career plans.


## Contribution

In this project, I mainly work on the [Volatility Analysis](https://github.com/guanzhangszhao/YoungNRich/commit/9240c4e4af6b67d76f735bb807d6d1733cdb19bf) part for finding the most suitable model in our project. I've created some of the preparation functions together with chelsea, and I mainly did the code contribution parts as well as different MSE plots.
