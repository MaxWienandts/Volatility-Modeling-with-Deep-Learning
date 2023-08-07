# Volatility-Modeling-with-Deep-Learning

Project Proposal Title: Volatility Modeling with Deep Learning

Group:
Autumn Dorsey
Loralee Ryan
Max Wienandts
Ronan Fonseca

Problem Statement:
Is it possible to make a prediction model to forecast security volatility for the next 4 weeks?

Motivation
Volatility, the measurement of the magnitude of price fluctuations over time, is conceptually the "second derivative of price" but is often easier to model than price data itself. The interactions that lead to the price of a security are multifaceted, multifactorial, nonlinear and often discontinuous. A shock to the market can cause the price of one security to fall while causing the price of another to spike at the same time. Modeling this is hard - but modeling that a shock to the market will cause a volatility jump in both securities is considerably easier, because volatility ignores the direction of the movement.
Volatility is also a tradeable asset itself, thanks to the creation of financial instruments that track it.
Unlike other types of financial models, volatility models can be adapted to account for both long term (multi-year patterns) or short term (the movement a security even over a couple of minutes). They are also designed to capture extreme events, unlike many price models which tend to lose accuracy during a shock to the market (such as Covid-19!).
Financial markets have many hidden and complex patterns in the data. We have learned about many different methods for revealing complex interactions. Financial data is abundant, popular, and notoriously difficult to work with. We are curious to see what some of the models we have learned about will reveal when applied to this famously difficult arena.
