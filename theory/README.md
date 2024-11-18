# List of theory topics

**:file_folder: This [Google Drive Folder](https://drive.google.com/drive/u/1/folders/1rbD4yqTNoNPsZ-S_qtPYBvO3CTvs-s4S) contains the slides for the 2024 lectures.**

There are 11 theory sessions of 2 hours each. They will all take place face-to-face. Please bring your laptop.

**Before each class, there are short videos you should watch.** They are up to 20 minutes in total, and watching them requires some preparation/scheduling on your part. Please set aside time in your schedule to watch these videos before coming to class, ideally on the day before.

**During class,** I will present the contents using slides and we will do together some exercises using Nearpod or Google Spreadsheets. Please avoid distractions: place your phone in airplane mode, close all other windows in your computer, and try to stay focused. We will pause frequently during the session to help you regain focus. In one of the sessions, a *midterm exam* will be taken, and at the end of the course, a *final exam* will be taken. The exam questions are based exclusively on the materials shown or discussed in the lectures during class.

**After each session, there is some reading for you to do.** These readings will be much easier after you have attended each lecture, will bring depth to what you learn in class, and will help you remember these contents better. Think of these readings as a form of continuous studying that will save you time and effort when preparing for the exams.

**:file_folder: This [Google Drive Folder](https://drive.google.com/drive/u/1/folders/1rbD4yqTNoNPsZ-S_qtPYBvO3CTvs-s4S) contains the slides for the 2024 lectures.**

## Session 1: Introduction

### Before class

* :tv: Watch this 6-minutes presentation of the [Knowledge Discovery in Databases](https://www.youtube.com/watch?v=0PDq4wYZqP0) process by Ali Soofastaei
* Take a look at the list of [theory topics](./),  [practice sessions](../practicum/README.md), and [evaluation rules](../upf/upf-evaluation.md)

### During class

* **Lecture TT01: The Data Mining Process**
* Course overview
   * Overview of [theory topics](./)
   * Overview of [practice sessions](../practicum/README.md)
   * Overview of [evaluation rules](../upf/upf-evaluation.md)
* **Lecture TT02: Data, Methods, and Scenarios**
   * Exercise: number of columns
   * Exercise: confidence of a rule
   * Exercise: which ones are data mining tasks? (pin board)
* **Lecture TT03: Data Preparation - Data Types**
   * Exercise: compute binning (spreadsheet)

### After class

* Read chapter 1 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read the beginning of chapter 2 (up to section 2.2 inclusive) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* :computer: Strongly recommended to help you prepare for the practice sessions: [tutorials 1 and 2](http://www.cse.msu.edu/~ptan/dmbook/software/) of the book by Tan et al. These tutorials are an introduction to Python, which you should do unless you are very comfortable with this language, and about `numpy` and `pandas`, which will save you a ton of time in the practices.
* Read [data sources and biases](http://trustworthymachinelearning.com/trustworthymachinelearning-04.htm) free book chapter of the Trustworthy Machine Learning book.

## Session 2: Data cleaning

### Before class

* :tv: Watch this 14-minutes talk and demo on [Cleaning Data](https://www.youtube.com/watch?v=zVImIQuqjQ0) by Mike Pound; his examples use R but the same can be done in many languages.

### During class

* **Lecture TT04: Data Preparation - Integration and Cleaning**
   * Exercise: how to handle missing data
* **Lecture TT05: Data Preparation - Reduction and Transformation**
* **Lecture TT06: Similarity - Numerical Data**
   * Exercise: compute Lp norm

### After class

* Read the rest of chapter 2 (sections 2.3 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read the beginning of chapter 3 (up to section 3.2.1) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* :tv: If the concept of *dimensionality reduction* still sounds pretty alien to you, watch this 12-minutes lecture on [dimensionality reduction](https://www.youtube.com/watch?v=yLdOS6xyM_Q) by Jure Leskovec

### Optional/additional material

* :computer: [Tutorials 3 and 4](http://www.cse.msu.edu/~ptan/dmbook/software/) of the book by Tan et al. cover issues of data exploration and data pre-processing. The latter is quite similar to our first practice session, but uses a different dataset.

## Session 3: Near duplicates

### Before class

* :tv: Watch this 3-minutes video on [Jaccard similarity](https://www.youtube.com/watch?v=Ah_4xqvS1WU) by Victor Axelsson

### During class

* **Lecture TT07: Similarity - Beyond Numerical Data**
   * Exercise: compute Jaccard similarity
* **Lecture TT08: Finding Near-Duplicates**
   * Exercise: compute signature matrix
* **Lecture TT09: Locality-Sensitive Hashing**

### After class

* Read the rest of chapter 3 (section 3.2.2 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read [chapter 3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch3n.pdf)

### Optional/additional material

* :tv: Watch this 37-minutes lecture by Ben Langmead on [Jaccard coefficient and min-hashing](https://www.youtube.com/watch?v=aTwRpqUnQX8)
* :tv: Watch Jeffrey D. Ullman, a famous computer scientist and co-author of one of the books we use in the course and of this method specifically describe this near-duplicate finding method. Two 50-minutes videos: [part 1](https://www.youtube.com/watch?v=bQAYY8INBxg), [part 2](https://www.youtube.com/watch?v=MaqNlNSY4gc).
* See presentation **TT10: Locality-Sensitive Hashing (Additional)**

## Session 4: Itemsets

### Before class

* :tv: Watch the first 8 minutes of this animated video [explanation of the Apriori algorithm](https://www.youtube.com/watch?v=WGlMlS_Yydk), for an explanation of the concepts of itemsets, support, confidence, and lift.

### During class

* **Lecture TT11: Itemsets**
   * Exercise: compute itemset support (spreadsheet)
   * Exercise: compute maximal itemsets
* **Lecture TT12: Association Rules**
   * Exercise: compute support, confidence, and lift of a rule

### After class

* Read the rest of chapter 3 (section 3.2.2 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read [chapter 3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch3n.pdf)
* Read [section 6.1 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch6.pdf)
   * **Or** read section 4.1 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Session 5: Association rules mining

### Before class

* :tv: Watch the rest of the [explanation of the Apriori algorithm](https://youtu.be/WGlMlS_Yydk?t=478), starting at mark 07:58.

### During class

* **Lecture TT13: Association Rules Mining**
   * Exercise: prove confidence monotonicity
   * Exercise: execute Apriori algorithm (spreadsheet)
* **Lecture TT14: Improved Association Rules Mining**
   * Exercise: indicate which items are visited in a hash tree

### After class

* Read [section 6.2 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch6.pdf)
   * **Or** read section 4.2-4.4 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* See presentation **TT15: Extending Association Rules Analysis (Additional)**
* If you did not understand well the hash tree, watch these four videos (18 minutes in total) from the J. Academy: [support counting using hash tree (part 1)](https://www.youtube.com/watch?v=qPIp3Wq64Vs), [support counting using hash tree (part 2)](https://www.youtube.com/watch?v=AIqOQA5mnGA), [hash tree generation step by step](https://www.youtube.com/watch?v=btW-uU1dhWI), [hash tree and support counting](https://www.youtube.com/watch?v=d040C7c06e4); if you find this easy to follow check their entire [playlist on association rules mining](https://www.youtube.com/playlist?list=PLk6n8LK7VfVg8r39BtrJUBrjyShlZ0nqt).

## Session 6: Mid-term exam (Tue October 22nd, 2024 08:30-10:30)

### Before class

Study on your own TT01-TT09, TT11-TT14, try to solve exams from past years. Ask your questions in the forum.

The exam will not include TT10.

### During class

We will have a mid-term exam, with no class after the mid-term.

## Session 7: Recommender systems

### Before class

* :tv: Watch the 6-minutes presentation of an [introduction to recommender systems](https://www.youtube.com/watch?v=U-yq3I9QugQ)
* :tv: Watch the 17-minutes [introductory lecture to recommender systems](https://www.youtube.com/watch?v=1JRrCEgiyHM) by Anand Rajaraman

### During class

* **Lecture TT16: Recommender Systems**
   * Exercise: content-based single-user recommendations (spreadsheet)
* **Lecture TT17: Recommender Systems - Interaction-Based**
   * Exercise: recommender based on user similarity (spreadsheet)

### After class

* Read [sections 9.1-9.3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)
* :tv: Watch the two 21-minutes lectures on [content-based recommender systems](https://www.youtube.com/watch?v=2uxXPzm-7FY) and [collaborative filtering](https://www.youtube.com/watch?v=h9gpufJFF-0) by Anand Rajaraman

## Session 8: Recommender systems (cont.) + Outlier analysis

### Before class

* :tv: Watch the 7-minutes lecture on [outlier analysis](https://www.youtube.com/watch?v=R_XKJ_l1jBc) by Gourab Nath, discussing why outliers occur

### During class

* :tv: We will watch this 8-minutes presentation on [how recommender systems work](https://www.youtube.com/watch?v=n3RKsY2H-NE) by Art of the Problem, which describes a factorization-based (latent-factors based) method
* **Lecture TT18: Recommender Systems - Latent Factors**
* **Lecture TT19: Outliers - Extreme Values**
   * Exercise: outliers using z-score (spreadsheet)
* **Lecture TT20: Outliers - Probability Density Methods**
   * Exercise: clustering-based outlier detection (spreadsheet)

### After class

* Read [sections 9.4-9.5 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)
* Read chapter 8 (except 8.5) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* :tv: If you did not understand the latent factors method, watch this 33-minutes presentation on [How does Netflix recommend movies? Matrix Factorization](https://www.youtube.com/watch?v=ZspR5PZemcs)

## Session 9: Outlier analysis (cont.) + Data streams

## Before class

* :tv: Watch this 14-minutes talk and demo on [isolation forests in Python](https://www.youtube.com/watch?v=TP3wdwD8JVY)
* :tv: Watch this 4-minutes animation on [reservoir sampling](https://www.youtube.com/watch?v=A1iwzSew5QY) by Eric Laber

## During class

* **Lecture TT21: Outliers - Density- and Isolation-Based Methods**
   * Exercise: isolation forest example
* **Lecture TT22: Data Streams**
   * Exercise: sampling at a fixed rate
* **Lecture TT23: Data Streams - Reservoir Sampling**
   * Exercise: probabilities in a reservoir sample

## After class

* Read [sections 4.1 and 4.2 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch4.pdf)
* Read section 8.5 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Optional/additional material

* Read the original ICDM 2008 [paper on isolation forests](https://scholar.google.com/scholar?cluster=11545522615192696786&hl=en&as_sdt=0,5) -- do not worry if you cannot follow all the details

## Session 10: Streams (cont.) + Time series mining

### Before class

* :tv: Watch this 3-minutes quick presentation on [bloom filters](https://www.youtube.com/watch?v=-SuTGoFYjZs) by Cube Drone

### During class

* **Lecture TT24: Data Streams - Bloom Filters**
   * :tv: We will watch this 6-minutes [animation on Bloom Filters](https://www.youtube.com/watch?v=kfFacplFY4Y)
   * Exercise: Bloom filter collisions
* **Lecture TT25: Data Streams - Probabilistic Counting**
   * Exercise: ideas for simple probabilistic counting
* **Lecture TT27: Time Series Analysis**
   * Exercise: smooth a time series (spreadsheet)

### After class

* Read [sections 4.3 and 4.4 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch4.pdf)
* Read sections 14.1 and 14.2 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* See presentation **TT26: Data Streams - Estimating Moments (Additional)**

## Session 11: Time series mining (cont.)

### Before class

* :tv: Watch this 7-minutes talk on the [moving average model](https://www.youtube.com/watch?v=voryLhxiPzE) and this 9-minutes talk on the [autoregressive model](https://www.youtube.com/watch?v=5-2C4eO4cPQ).

### During class

* **Lecture TT28: Time Series - Similarity**
   * Example: dynamic time warping (spreadsheet)
* **Lecture TT29: Time Series - Forecasting**
   * Example: simple auto-regressive model (spreadsheet)

### After class

* Read section 14.3 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Final exam (December 11th, 09:30-11:30)

The [date of the final exam](https://www.upf.edu/web/etic/primer-trimestre-tic) is fixed by the School of Engineering. Please check their webpage for potential changes.

The final exam will include recommender systems, outlier analysis, data streams, and forecasting: topics TT16-TT25, TT27-TT29; it will not include topic TT26.

# Notes

:construction: Session numbers are approximate and subject to change. Materials should not be considered final until the end of the course.

[<img src="../upf/cc-by-80x15.png" width="80" height="15" hspace="4"/>](https://creativecommons.org/licenses/by/4.0/) Slides are available under a [Creative Commons](https://creativecommons.org/licenses/by/4.0/) license unless specified otherwise.

# Main bibliography

:blue_book: [Data Mining, The Textbook](https://www.springer.com/us/book/9783319141411) (2015) by Charu Agrawal. ISBN 978-3-319-14142-8. [Free Download](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

:ledger: [Mining of Massive Datasets SECOND EDITION](https://www.cambridge.org/core/books/mining-of-massive-datasets/C1B37BA2CBB8361B94FDD1C6F4E47922) (2014) by Leskovec et al. ISBN 978-1107077232. Online materials: [http://www.mmds.org/](http://www.mmds.org/). [Free Download](http://infolab.stanford.edu/~ullman/mmds/bookL.pdf)

# Additional bibliography

:orange_book: [Introduction to Data Mining SECOND EDITION](https://www.pearson.com/us/higher-education/program/Tan-Introduction-to-Data-Mining-2nd-Edition/PGM214749.html) (2019) by Tan et al. ISBN 978-0-13-312890-1. Online materials: [https://www-users.cs.umn.edu/~kumar001/dmbook/index.php](https://www-users.cs.umn.edu/~kumar001/dmbook/index.php)

:blue_book: [Data Mining and Machine Learning SECOND EDITION](https://dataminingbook.info/book_html/) (2020) by Zaki and Meira. ISBN 978-1108473989.

:notebook: [Data Mining Concepts and Techniques THIRD EDITION](https://www.elsevier.com/books/data-mining-concepts-and-techniques/han/978-0-12-381479-1) (2011) by Han et al. ISBN 978-0123814791.
