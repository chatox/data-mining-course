# List of theory topics

:construction: I am currently (July-August 2020) adapting these contents for the 2020 edition.

There are 11 theory sessions of 2 hours each. In one of the sessions, a *midterm exam* will be taken.

## Session 1: Introduction

### Before class

* :tv: Watch this 6-minutes introduction to the [Knowledge Discovery in Databases](https://www.youtube.com/watch?v=0PDq4wYZqP0) process by Ali Soofastaei
* Take a look at the list of [theory topics](./),  [practice sessions](../practicum/README.md), and [evaluation rules](../upf/upf-evaluation.md)

### During class

* Presentation TT01: introduction [odp](odp/tt01_introduction.odp)/[pdf](pdf/tt01_introduction.pdf)
* Course overview
   * Overview of [theory topics](./)
   * Overview of [practice sessions](../practicum/README.md)
   * Overview of [evaluation rules](../upf/upf-evaluation.md)
* Presentation TT02: data, methods, and scenarios [odp](odp/tt02_data_methods_scenarios.odp)/[pdf](pdf/tt02_data_methods_scenarios.pdf)
   * Nearpod open ended question: confidence of a rule
   * Nearpod time to climb: identify data mining tasks
* Presentation TT03: data preparation, data types [odp](odp/tt03_data_types.odp)/[pdf](pdf/tt03_data_types.pdf)
   * Google spreadsheet: compute binning

### After class

* Read chapter 1 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read the beginning of chapter 2 (up to section 2.2 inclusive) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* :computer: Strongly recommended to help you prepare for the practice sessions: [tutorials 1 and 2](http://www.cse.msu.edu/~ptan/dmbook/software/) of the book by Tan et al. These tutorials are an introduction to Python, which you should do unless you are very comfortable with this language, and about `numpy` and `pandas`, which will save you a ton of time in the practices.

## Session 2: Data cleaning

### Before class

* :tv: Watch this 14-minutes video on [Cleaning Data](https://www.youtube.com/watch?v=zVImIQuqjQ0) by Mike Pound; his examples use R but the same can be done in many languages.
* :tv: Watch this 5-minutes video on [Cleaning Data with Python and Pandas](https://www.youtube.com/watch?v=ZOX18HfLHGQ); the video ends with an advert for an online course that I do not endorse.

### During class

* Presentation TT04: data integration and cleaning [odp](odp/tt04_integration_cleaning.odp)/[pdf](pdf/tt04_integration_cleaning.pdf)
   * Nearpod collaborate: how to handle missing data
* Presentation TT05: data reduction and transformation [odp](odp/tt05_reduction.odp)/[pdf](pdf/tt05_reduction.pdf)
* Presentation TT06: similarity computation on numerical data [odp](odp/tt06_sim_numerical.odp)/[pdf](pdf/tt06_sim_numerical.pdf)
   * Nearpod collaborate: compute Lp norm

### After class

* Read the rest of chapter 2 (sections 2.3 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read the beginning of chapter 3 (up to section 3.2.1) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* :computer: [Tutorials 3 and 4](http://www.cse.msu.edu/~ptan/dmbook/software/) of the book by Tan et al. cover issues of data exploration and data pre-processing. The latter is quite similar to our first practice session, but uses a different dataset.

## Session 3: Near duplicates

### Before class

* :tv: Watch this 37-minutes video by Ben Langmead on [Jaccard coefficient and min-hashing](https://www.youtube.com/watch?v=aTwRpqUnQX8)

### During class

* Presentation TT07: similarity computation beyond numerical data [odp](odp/tt07_sim_beyond_numerical.odp)/[pdf](pdf/tt07_sim_beyond_numerical.pdf)
   * Nearpod collaborate: compute Jaccard similarity
* Presentation TT08: finding near-duplicates [odp](odp/tt08_near_duplicates.odp)/[pdf](pdf/tt08_near_duplicates.pdf)
   * Nearpod draw it: compute signature matrix
* Presentation TT09: locality-sensitive hashing [odp](odp/tt09_locality_sensitive_hashing.odp)/[pdf](pdf/tt09_locality_sensitive_hashing.pdf)

### After class

* Read the rest of chapter 3 (section 3.2.2 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read [chapter 3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch3n.pdf)

### Optional/additional material

* :tv: Watch Jeffrey D. Ullman, a famous computer scientist and co-author of one of the books we use in the course and of this method specifically describe this near-duplicate finding method. Two 50-minutes videos: [part 1](https://www.youtube.com/watch?v=bQAYY8INBxg), [part 2](https://www.youtube.com/watch?v=MaqNlNSY4gc).
* See presentation TT10: locality-sensitive hashing additional materials [odp](odp/tt10_locality_sensitive_hashing_additional.odp)/[pdf](pdf/tt10_locality_sensitive_hashing_additional.pdf)

## Session 4: Itemsets

### Before class

* :tv: Watch ...

### During class

* Presentation TT11: itemsets [odp](odp/tt011_itemsets.odp)/[pdf](pdf/tt11_itemsets.pdf)
   * Google spreadsheet: compute itemset support
   * Nearpod collaborate: compute maximal itemsets
* Presentation TT12: association rules [odp](odp/tt012_association_rules.odp)/[pdf](pdf/tt12_association_rules.pdf)
   * Nearpod draw-it: compute support, confidence, and lift of a rule

### After class

* Read the rest of chapter 3 (section 3.2.2 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read [chapter 3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch3n.pdf)
* Read [section 6.1 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch6.pdf)
   * Or read section 4.1 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Session 5: Association rules mining

## Session 6: Mid-term exam

# OLD MATERIAL BELOW THIS LINE

There are 11 theory sessions of 2 hours each. In two of the sessions, *midterm exams* will be taken.

| Topic | Contents |  Sess. (dur.) | Materials |
|-----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------|---------------------------------------------------------------------------------------------------|
| **TT06 Association rule mining** | A priori algorithm; Interesting patterns | 5 (2h) | [pdf](pdf/tt06_association_rule_mining.pdf) [odp](tt06_association_rule_mining.odp) |
|  | *First midterm exam*: Topics TT01-TT04 | <strike>5</strike> <strike>6</strike> 7 (1h) |  |
| **TT07 Extending association analysis** | Interestingness measures; Categorical and continuous attributes; Min-Apriori; Mining rules on a hierarchy | <strike>6</strike> (on your own -- not evaluated) | [pdf](pdf/tt07_extending_association_analysis.pdf) [odp](tt07_extending_association_analysis.odp) |
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
