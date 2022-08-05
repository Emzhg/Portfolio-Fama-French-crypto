# Portfolio-Fama-French-crypto

Files for F-F datasets are available here: http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html#Research

Data crypto obtained from:
https://github.com/sstoeckl/crypto2

Using this github repository download the oldest 100 tokens

coin_hist <- crypto_history(limit=100, finalWait=FALSE)

write.csv(coin_hist, "crypto.csv")
