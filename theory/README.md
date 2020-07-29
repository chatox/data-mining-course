# List of theory topics

:construction: I am currently (July-August 2020) adapting these contents for the 2020 edition.

There are 11 theory sessions of 2 hours each. In one of the sessions, a *midterm exam* will be taken. At the end of the course, a *final exam* will be taken. Exam questions are based only on the materials shown or discussed in the lectures during class -- all other videos and readings are optional.

## Session 1: Introduction

### Before class

* :tv: Watch this 6-minutes presentation of the [Knowledge Discovery in Databases](https://www.youtube.com/watch?v=0PDq4wYZqP0) process by Ali Soofastaei
* Take a look at the list of [theory topics](./),  [practice sessions](../practicum/README.md), and [evaluation rules](../upf/upf-evaluation.md)

### During class

* Lecture TT01: introduction [odp](odp/tt01_introduction.odp)/[pdf](pdf/tt01_introduction.pdf)
* Course overview
   * Overview of [theory topics](./)
   * Overview of [practice sessions](../practicum/README.md)
   * Overview of [evaluation rules](../upf/upf-evaluation.md)
* Lecture TT02: data, methods, and scenarios [odp](odp/tt02_data_methods_scenarios.odp)/[pdf](pdf/tt02_data_methods_scenarios.pdf)
   * Nearpod open ended question: confidence of a rule
   * Nearpod time to climb: identify data mining tasks
* Lecture TT03: data preparation, data types [odp](odp/tt03_data_types.odp)/[pdf](pdf/tt03_data_types.pdf)
   * Google spreadsheet: compute binning

### After class

* Read chapter 1 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read the beginning of chapter 2 (up to section 2.2 inclusive) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* :computer: Strongly recommended to help you prepare for the practice sessions: [tutorials 1 and 2](http://www.cse.msu.edu/~ptan/dmbook/software/) of the book by Tan et al. These tutorials are an introduction to Python, which you should do unless you are very comfortable with this language, and about `numpy` and `pandas`, which will save you a ton of time in the practices.

## Session 2: Data cleaning

### Before class

* :tv: Watch this 14-minutes talk and demo on [Cleaning Data](https://www.youtube.com/watch?v=zVImIQuqjQ0) by Mike Pound; his examples use R but the same can be done in many languages.
* :tv: Watch this 5-minutes presentation and demo on [Cleaning Data with Python and Pandas](https://www.youtube.com/watch?v=ZOX18HfLHGQ); the video ends with an advert for an online course that I do not endorse.

### During class

* Lecture TT04: data integration and cleaning [odp](odp/tt04_integration_cleaning.odp)/[pdf](pdf/tt04_integration_cleaning.pdf)
   * Nearpod collaborate: how to handle missing data
* Lecture TT05: data reduction and transformation [odp](odp/tt05_reduction.odp)/[pdf](pdf/tt05_reduction.pdf)
* Lecture TT06: similarity computation on numerical data [odp](odp/tt06_sim_numerical.odp)/[pdf](pdf/tt06_sim_numerical.pdf)
   * Nearpod collaborate: compute Lp norm

### After class

* Read the rest of chapter 2 (sections 2.3 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read the beginning of chapter 3 (up to section 3.2.1) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* :tv: If the concept of *dimensionality reduction* still sounds pretty alien to you, watch this 12-minutes lecture on [dimensionality reduction](https://www.youtube.com/watch?v=yLdOS6xyM_Q) by Jure Leskovec

### Optional/additional material

* :computer: [Tutorials 3 and 4](http://www.cse.msu.edu/~ptan/dmbook/software/) of the book by Tan et al. cover issues of data exploration and data pre-processing. The latter is quite similar to our first practice session, but uses a different dataset.

## Session 3: Near duplicates

### Before class

* :tv: Watch this 37-minutes lecture by Ben Langmead on [Jaccard coefficient and min-hashing](https://www.youtube.com/watch?v=aTwRpqUnQX8)

### During class

* Lecture TT07: similarity computation beyond numerical data [odp](odp/tt07_sim_beyond_numerical.odp)/[pdf](pdf/tt07_sim_beyond_numerical.pdf)
   * Nearpod collaborate: compute Jaccard similarity
* Lecture TT08: finding near-duplicates [odp](odp/tt08_near_duplicates.odp)/[pdf](pdf/tt08_near_duplicates.pdf)
   * Nearpod draw it: compute signature matrix
* Lecture TT09: locality-sensitive hashing [odp](odp/tt09_locality_sensitive_hashing.odp)/[pdf](pdf/tt09_locality_sensitive_hashing.pdf)

### After class

* Read the rest of chapter 3 (section 3.2.2 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read [chapter 3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch3n.pdf)

### Optional/additional material

* :tv: Watch Jeffrey D. Ullman, a famous computer scientist and co-author of one of the books we use in the course and of this method specifically describe this near-duplicate finding method. Two 50-minutes videos: [part 1](https://www.youtube.com/watch?v=bQAYY8INBxg), [part 2](https://www.youtube.com/watch?v=MaqNlNSY4gc).
* See presentation TT10: locality-sensitive hashing additional materials [odp](odp/tt10_locality_sensitive_hashing_additional.odp)/[pdf](pdf/tt10_locality_sensitive_hashing_additional.pdf)

## Session 4: Itemsets

### Before class

* :tv: Watch the first 8 minutes of this animated video [explanation of the Apriori algorithm](https://www.youtube.com/watch?v=WGlMlS_Yydk), for an explanation of the concepts of itemsets, support, confidence, and lift.

### During class

* Lecture TT11: itemsets [odp](odp/tt11_itemsets.odp)/[pdf](pdf/tt11_itemsets.pdf)
   * Google spreadsheet: compute itemset support
   * Nearpod collaborate: compute maximal itemsets
* Lecture TT12: association rules [odp](odp/tt12_association_rules.odp)/[pdf](pdf/tt12_association_rules.pdf)
   * Nearpod draw-it: compute support, confidence, and lift of a rule

### After class

* Read the rest of chapter 3 (section 3.2.2 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read [chapter 3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch3n.pdf)
* Read [section 6.1 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch6.pdf)
   * **Or** read section 4.1 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Session 5: Association rules mining

### Before class

* :tv: Watch the rest of the [explanation of the Apriori algorithm](https://youtu.be/WGlMlS_Yydk?t=478), starting at mark 07:58.

### During class

* Lecture TT13: association rules mining [odp](odp/tt13_association_rules_mining.odp)/[pdf](pdf/tt13_association_rules_mining.pdf)
   * Nearpod draw-it: prove confidence monotonicity
   * Google spreadsheet: execute Apriori algorithm
* Lecture TT14: speeding up association rules mining [odp](odp/tt14_improved_rules_mining.odp)/[pdf](pdf/tt14_improved_rules_mining.pdf)
   * Nearpod draw-it: indicate which items are visited in a hash tree

### After class

* Read [section 6.2 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch6.pdf)
   * **Or** read section 4.2-4.4 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* See presentation TT15: extending association analysis [odp](odp/tt015_extended_association_analysis.odp)/[pdf](pdf/tt15_extended_association_analysis.pdf)
* If you did not understand well the hash tree, watch these four videos (18 minutes in total) from the J. Academy: [support counting using hash tree (part 1)](https://www.youtube.com/watch?v=qPIp3Wq64Vs), [support counting using hash tree (part 2)](https://www.youtube.com/watch?v=AIqOQA5mnGA), [hash tree generation step by step](https://www.youtube.com/watch?v=btW-uU1dhWI), [hash tree and support counting](https://www.youtube.com/watch?v=d040C7c06e4); if you find this easy to follow check their entire [playlist on association rules mining](https://www.youtube.com/playlist?list=PLk6n8LK7VfVg8r39BtrJUBrjyShlZ0nqt).

## Session 6: Mid-term exam

### Before class

Study on your own TT01-TT09, TT11-TT14, try to solve exams from past years. Ask your questions in the forum.

### During class

We will have a mid-term exam covering topics: TT01-TT09, TT11-TT14.

## Session 7: Recommender systems

### Before class

* :tv: Watch the 6-minutes presentation of an [introduction to recommender systems](https://www.youtube.com/watch?v=U-yq3I9QugQ)
* :tv: Watch the 17-minutes [introductory lecture to recommender systems](https://www.youtube.com/watch?v=1JRrCEgiyHM) by Anand Rajaraman

### During class

* Lecture TT16: recommender systems [odp](odp/tt16_recommender_systems.odp)/[pdf](pdf/tt16_recommender_systems.pdf)
   * Google spreadsheet: content-based single-user recommendations
* Lecture TT17: interaction-based recommender systems [odp](odp/tt17_interaction_based_recommenders.odp)/[pdf](pdf/tt17_interaction_based_recommenders.pdf)
   * Google spreadsheet: recommender based on user similarity

### After class

* Read [sections 9.1-9.3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)
* :tv: Watch the two 21-minutes lectures on [content-based recommender systems](https://www.youtube.com/watch?v=2uxXPzm-7FY) and [collaborative filtering](https://www.youtube.com/watch?v=h9gpufJFF-0) by Anand Rajaraman

## Session 8: Recommender systems (cont.) + Outlier analysis

### Before class

* :tv: Watch the 8-minutes presentation on [how recommender systems work](https://www.youtube.com/watch?v=n3RKsY2H-NE) by Art of the Problem, which describes a factorization-based method
* :tv: Watch the 7-minutes lecture on [outlier analysis](https://www.youtube.com/watch?v=R_XKJ_l1jBc) by Gourab Nath, discussing why outliers occur

### During class

* Lecture TT18: latent-factors based recommender systems [odp](odp/tt18_latent_factors_recommenders.odp)/[pdf](pdf/tt18_latent_factors_recommenders.pdf)
* Lecture TT19: outliers introduction and extreme value analysis [odp](odp/tt19_outliers_extreme_values.odp)/[pdf](pdf/tt19_outliers_extreme_values.pdf)
   * Google spreadsheet: outliers using z-score
* Lecture TT20: probability and density-based methods [odp](odp/tt20_outliers_probability_density.odp)/[pdf](pdf/tt20_outliers_probability_density.pdf)

### After class

* Read [sections 9.4-9.5 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)
* Read chapter 8 (except 8.5) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Session 9: Outlier analysis (cont.) + Data streams

## Before class

* :tv: Watch this 14-minutes talk and demo on [isolation forests in Python](https://www.youtube.com/watch?v=TP3wdwD8JVY)
* :tv: Watch this 4-minutes animation on [reservoir sampling](https://www.youtube.com/watch?v=A1iwzSew5QY) by Eric Laber

## During class

* Lecture TT21: isolation and distance-based methods [odp](odp/tt21_outliers_isolation.odp)/[pdf](pdf/tt21_outliers_isolation.pdf)
   * Nearpod draw-it: isolation forest example
* Lecture TT22: data streams [odp](odp/tt22_streams.odp)/[pdf](pdf/tt22_streams.pdf)
   * Nearpod collaborate: probability of a false positive or a false negative
* Lecture TT23: reservoir sampling [odp](odp/tt23_reservoir_sampling.odp)/[pdf](pdf/tt23_reservoir_sampling.pdf)
   * Nearpod open-ended question: probabilities in a reservoir sample

## After class

* Read section except 8.5 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Optional/additional material

* Read the original ICDM 2008 [paper on isolation forests](https://scholar.google.com/scholar?cluster=11545522615192696786&hl=en&as_sdt=0,5) -- do not worry if you cannot follow all the details
* See presentation TT26: moments estimation [odp](odp/tt26_estimating_moments.odp)/[pdf](pdf/tt26_estimating_moments.pdf)

## Session 10: Streams (cont.) + Time series mining

### Before class
* :tv: Watch this 3-minutes quick presentation on [bloom filters](https://www.youtube.com/watch?v=-SuTGoFYjZs) by Cube Drone

### During class 

* Lecture TT24: bloom filters [odp](odp/tt24_bloom_filters.odp)/[pdf](pdf/tt24_bloom_filters.pdf)
   * :tv: We will watch this 6-minutes [animation on Bloom Filters](https://www.youtube.com/watch?v=kfFacplFY4Y)
*

## Session 11: Spectral Clustering

# OLD MATERIAL BELOW THIS LINE

There are 11 theory sessions of 2 hours each. In two of the sessions, *midterm exams* will be taken.

| Topic | Contents |  Sess. (dur.) | Materials |
|-----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------|---------------------------------------------------------------------------------------------------|
| **TT08 Recommender systems** | Content-based recommendations; Interaction-based recommendations (user-based, item-based); Latent factors methods; Evaluation | 7-8 (2h) | [pdf](pdf/tt08_recommender_systems.pdf) [odp](tt08_recommender_systems.odp) |
| **TT09 Outlier analysis** | Extreme values analysis; Isolation forest; Clustering-based methods; Distance-based methods; Density-based methods; Outlier validity | 9-10 (2h) | [pdf](pdf/tt09_outlier_detection.pdf) [odp](tt09_outlier_detection.odp) |
|  | *Second midterm exam*: Topics TT05, TT06, TT08 | 9 (1h) |  |
| **TT10 Streams** | Load shedding; Sampling (fixed proportion); Sampling (fixed size); Bloom filters; Probabilistic counting; Moments | 10-11 (2h) | [pdf](pdf/tt10_streams.pdf) [odp](tt10_streams.odp) |
| **TT11 Time series mining** | Series preparation (interpolation, smoothing); Dynamic time warping; Time series forecasting; Event detection | 11 (1h) | [pdf](pdf/tt11_time_series.pdf) [odp](tt11_time_series.odp) |
| **TT12 Spectral graph clustering** | Graph projections | <strike>11? (1h)?</strike> (on your own -- not evaluated) | [pdf](pdf/tt12_spectral_graph_clustering.pdf) [odp](tt12_spectral_graph_clustering.odp) |
|  | *Final exam*: Topics TT01-TT06, TT08-TT11 | Ex (2h) |  |

Note that session numbers are approximate and subject to change.

[<img src="../upf/cc-by-80x15.png" width="80" height="15" hspace="4"/>](https://creativecommons.org/licenses/by/4.0/) Slides available under a [Creative Commons](https://creativecommons.org/licenses/by/4.0/) license unless specified otherwise.

# Bibliography

:blue_book: [Data Mining, The Textbook](https://www.springer.com/us/book/9783319141411) (2015) by Charu Agrawal. ISBN 978-3-319-14142-8. [Free Download](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

:ledger: [Mining of Massive Datasets SECOND EDITION](https://www.cambridge.org/core/books/mining-of-massive-datasets/C1B37BA2CBB8361B94FDD1C6F4E47922) (2014) by Leskovec et al. ISBN 978-1107077232. Online materials: [http://www.mmds.org/](http://www.mmds.org/). [Free Download](http://infolab.stanford.edu/~ullman/mmds/bookL.pdf)

:orange_book: [Introduction to Data Mining SECOND EDITION](https://www.pearson.com/us/higher-education/program/Tan-Introduction-to-Data-Mining-2nd-Edition/PGM214749.html) (2019) by Tan et al. ISBN 978-0-13-312890-1. Online materials: [https://www-users.cs.umn.edu/~kumar001/dmbook/index.php](https://www-users.cs.umn.edu/~kumar001/dmbook/index.php)

:blue_book: [Data Mining and Machine Learning SECOND EDITION](https://dataminingbook.info/book_html/) (2020) by Zaki and Meira. ISBN 978-1108473989.

:notebook: [Data Mining Concepts and Techniques THIRD EDITION](https://www.elsevier.com/books/data-mining-concepts-and-techniques/han/978-0-12-381479-1) (2011) by Han et al. ISBN 978-0123814791.
