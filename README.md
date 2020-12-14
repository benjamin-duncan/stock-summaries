# stock-summaries
This project aims to offer a visual summary of historical stock data from FTSE100 companies for the previous 12 months (with full offering of indices and time range subject to change). This will be achieved by using an algorithm to detect large changes in stock prices, searching the web for articles which describe the events causing the change in prices and creating a text summary for all notable events.

The initial phase of this project can be broken down into three stages:

Creating the algorithm to detect events, with suitable granularity to generate up to ten events.

Search the web using a web crawler or similar methods to pull text from articles corresponding to events.
Note: initially, the algorithm will not consider where events affected the market as a whole, the industry or the individual company.

Create summary of articles using NLP (Natural Language Processing).


For implementation python will be used initially, with an eventual implementation using an API via Django or similar, although the system architecture can be decided further down the line.
