# Developing a Smart ETF Recommender: A Web Mining and Machine Learning Approach

## Project Walk Through: [YouTube](https://youtu.be/emTV9VipE90)

## Project Description:

This project centers around a pressing challenge in the finance sector: improving decision-making for investors purchasing Exchange Traded Funds (ETFs). We've designed and implemented an innovative ETF Recommender to assist investors in identifying similar ETFs and reveal potential benefits such as lower expense ratios when switching.

**Key objectives:**

- Web Mining for ETF Data: Harnessing the power of web scraping, we extract crucial information about ETF holdings from multiple sources, including iShares and Investco. We have also implemented solutions to avoid spamming and preserve partial results, ensuring a seamless and efficient data collection process.

- Computing ETF Similarity: Leveraging advanced metrics such as Jaccard similarity and Cosine similarity, we devise a method to compute the similarity between ETFs. This comparison not only includes individual holdings but also factors in the weightings of those holdings.

- Building an ETF Recommender: Based on the similarity computations, we develop an ETF Recommender that suggests similar ETFs when an investor is about to buy a specific ETF. The recommender system operates for a broad universe of ETFs, including SPY, QQQ, ARKK, IBB, DIA, IWM, XLF, and RTH.

- Rationality in Investment Behavior: The project delves into the psychology of investing. Specifically, we evaluate if the behavior of investors wishing to buy QQQ is rational, and consider the limits of rationality in financial decision making.

- Automated and Repeatable Data Pipeline: To ensure our work is future-proof, all steps from data acquisition, cleaning, analysis to recommendation generation are automated using Python. This makes the process not only repeatable but also adaptable to future needs.

- Persistent and Reliable Data Storage: We opt for cloud-based storage solutions such as MongoDB for storing our data. This offers several advantages like accessibility, persistence, reliability, and indexing, handles the Website restrictions on "spamming", and eliminates the need for manual data manipulation.

- [Sheng Yun](https://github.com/nickShengY)
- [Xueqing Zhang](https://github.com/CathyXueqingZhang)
- [Jingyan Xu](https://github.com/horatioxu1122)
