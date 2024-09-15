# AI Stock Market Predictor

This stock market predictor was created thanks to a tutorial on YouTube (link: https://www.youtube.com/watch?v=1O_BenficgE&ab_channel=Dataquest)

There's many ways that this predictor can be improved, but since it was my first ever machine-learning project, I decided to keep it simple.

The main machine-learning technique used in this predictor was Decision Tree Learning, and more specifically the Random Forest algorithm, using the sklearn library in python.

I look very forward to experimenting with more AI/ML techniques on this project as well as others in the future! One technique I look forward to implementing is the use of genetic algorithms for trading, which essentially use a process akin to biological evolution for creating new trading strategies. In order to avoid overfitting, I will likely use walk-forward analysis

For those who want to build upon this model, there's several different ways it could be improved:

  1. Look at world-wide overnight markets instead of just U.S day market hours to see if you can correlate them
  2. You can add in news, by potentially implementing some NLP to analyze sentiment surrounding a company, and how it correlates with the stock over time
  3. You can add in some key components of the S&P500, like key stocks & key sectors. For example, if tech is in a downturn, it's possible that 6 months later, the     S&P500 goes down
  4. You can also increase the resolution by using hourly data, minute-to-minute data or even tick data (although it may not be cheap to get)
     
