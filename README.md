# Portfolio-Fama-French-crypto

Credit : 
Martin, R. A., (2021). PyPortfolioOpt: portfolio optimization in Python. Journal of Open Source Software, 6(61), 3066, https://doi.org/10.21105/joss.03066

Data crypto obtained from:
Files for F-F datasets are available here: http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html#Research

https://github.com/sstoeckl/crypto2

Using this github repository download the oldest 100 tokens

coin_hist <- crypto_history(limit=100, finalWait=FALSE)

write.csv(coin_hist, "crypto.csv")


