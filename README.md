# SI-simulation_investors
A Project for Network Science Course of Asian Institute of Management's Master of Science in Data Science 2023 

Using an SI Simulation on the investor network, an information flow simulation was conducted to determine the ideal set of investors startup companies should inform first. Different scenarios were conducted, and the spread of information was measured using two metrics: spread and relevance metric. The scenario that showed better information dissemination at the early simulation stages was when the initial investors were selected from the top eigenvector centrality of the same industry as the startup company. At t=6, this top scenario has 12 and 6 more informed investors than the random and top valuation scenarios.

The data for this study was sourced from Kaggle https://www.kaggle.com/datasets/ramjasmaurya/unicorn-startups, which contained information on Unicorn Startup companies such as their valuation, date started, base country, city location, industry, and their list of associated investors, which is limited to a maximum of four investors per startup company.
