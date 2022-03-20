# Sean Xin Yufeng

**Email** yufeng-xin@outlook.com

## EDUCATION BACKGROUND

### Xidian University

*Xi'an, China*

*08/2014–06/2018*

**Major: Internet of Things (School of Computer Science and Technology)**

- GPA: 3.1/4.0 (75/100)

- CCF certified software professional; Outstanding Student Leader
- Relevant courses
  - Data Structure (83)
  - Computer Organization and Architecture (95)
  -  Design and Analysis of Algorithms (81)
  - Artificial Intelligence (82)
  - Computer and Programming Fundamental (100)
  - Macroeconomics (85)
  - Software Engineering Paradigm and Technology in the Era of Big Data(83)
  - Data Warehouse and Data Mining
  - Computer System and Network Security

## WORK EXPERIENCE

### Hongkong Blue Wealth Asset Management Co., Ltd.

*Shenzhen, China*

*10/2019-Present*

**Data Engineer**

- Reviewed DeFi cryptocurrency material and explored the feasibility of using stock prediction paradigm to predict DeFi cryptocurrency price direction.
- Scraped twitter discussion data of DeFi Cryptocurrency using Tweepy API and obtained DeFi cryptocurrency historical data from *Binance*.
- Transformed DeFi cryptocurrency data into features like tweets discussion volume, tweet sentiment, and trading volume, and then input cleaned features to machine learning model like Neural Network/LGBM to train our prediction model.
- Optimized model parameter according to prediction accuracy and recall rate, transformed optimized model into trading strategy, and calculated strategy sharpe ratio, abnormal return, alpha, beta, information ratio, and maximum drawdown.
- Stored model prediction data into log file and MongoDB system, wrote a python script to automatically push real-time model buy and hold prediction signal to subscribed customer on Telegram Msg bot, and updated customer reading behavior to database.
- Wrote a system to aggregate real-time Defi cryptocurrency prices series from multiple exchanges and finished a python script to monitor data flow status like missing value and time out issues automatically.

### Beijing Tao Capital Co., Ltd.

*Beijing, China*

*07/2018-10/2019*

**Quantitative Developer**

- Improved trend following strategy performance via combing two trend recognition indicators: first difference return autocorrelation and weighted two side return correlation, and further optimized indicator informativeness through parameter Grid Search method.
- Applied pattern recognition algorithm-Perceptually Important Points(PIP) to detect future price series shapes such as “M”, “W”, and “√”, linked future price series shapes with the subsequent future return, and checked the subsequent future return statistics significant level by t-statistics.
- Crawled around 40,000 firm annual report data from SEC website, parsed HTML format annual report data into TXT file, and extracted annual report  “management discussion and analysis” text by python RegExp.
- Undertook other real-time market data calculation and statistical analysis tasks.eg. calculated announcement abnormal return, filtered portfolio stocks with extreme performance, updated fama-french factor model data.
- Maintained firm Mysql and MongoDB database, updated firm financial data from subscribed database like Wind, datastream, and Bloomberg weekly, drafted technical reports to facilitate team work.

## ACADEMIC PROJECT

### Prediction of Future Price Based on Insider Information: Evidence from HMM Model

*Xi'an, China*

*10/2017–05/2018*

**Under the supervision of Prof. Yu Qiang**

- Undergraduate thesis projects. Examined whether insider information proxied by large transactions could improve hidden Markov model (HMM) futures price prediction performance.
- Wrote Python program to obtain Futures daily prices and top transaction order data from UQER, cleaned /standardized raw historical prices data, and then constructed over 20 meaningful insider information features like large order *shortVol,longVol,turnoverVol* and general price features like average return and trading volume.
- Constructed both treatment and control group train datasets: The treatment group dataset included insider information features and general price features, while the control group only incorporated general price features.
- Applied K-Means algorithms to the treatment and control group dataset, labeled daily data point with K-Means cluster, and then transferred multi-dimensional features series into K-Means cluster label series, equivalent to Markov Model observation sequence series.
- Used the hmmlearn python package to fit the hidden Markov model based on future observation sequence series generated from treatment and control group train datasets respectively, evaluated model HMM model out of sample prediction accuracy, and found that HMM model consistently outperforms on treatment dataset in terms of prediction accuracy and backtest sharpe ratio.
- Conducted various robustness tests and sensitivity tests via changing K-Means algorithm K parameter, HMM Hidden State Number, and test sample periods. Empirical results confirmed that insider order could significantly improve model prediction performance.

### Human Resource Management Platform Development

*Xi'an, China*

*03/2016–07/2016*

**Under the supervision of Prof. Zhang Xiong**

- National College Student Innovation and Entrepreneurship Project. Designed and developed a human resource management cloud service platform, which included organization management, personnel management, salary management, time management, and performance management five modules. 
- Programed front page via Javascript/HTML and enabled inquiring, adding, modifying, deleting data from admin control panel.
- Used Mysql database stored operation data, established connections between webpage data and background data, and implemented calling and saving of the data. 
- Designed python code to automatically analyzed data, generated warn signal like late work delivery to related personnel.

## LEADERSHIP AND COMMUNITY ACTIVITIES

### University Science and Technology Association

*Xi'an, China*

*04/2015–04/2016*

**Deputy Head**

- Planned and organized multiple campus level activities, serving over 3000+ attendance in total.
- Interviewed entrepreneurial alumni and compiled the reports into a book.

### Other Extracurricular Activities

*Shenzhen/Dongguan/Huizhou, China*

*06/2019–10/2021*

**Participant**

- Finished professional racing course.
- Organized an informal racing group and won champion in a track day held by Guangdong Racing International Circuit.
- Organized a folk band and acted as a djembe drummer.

## KEY SKILLS

- Programming Language: Python(proficient), SQL, MongoDB, C#,C++
- Financial Database: Bloomberg, Datastream, Wind, CSMAR
- Language: Proficient in English Technical Materials (CET-6: 432) 
- Hobby: Badminton, Racing, and Djembe

