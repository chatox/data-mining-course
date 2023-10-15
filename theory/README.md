# List of theory topics

:construction: These materials should not be considered final until the end of the course. Materials from previous editions can be found in other branches of the repository for the course.

There are 11 theory sessions of 2 hours each. They will all take place face-to-face. Please bring your laptop.

**Before each class, there are short videos you should watch.** They are up to 20 minutes in total, and watching them requires some preparation/scheduling on your part. Please set aside time in your schedule to watch these videos before coming to class, ideally on the day before.

**During class,** I will present the contents using slides and we will do together some exercises using Nearpod or Google Spreadsheets. Please avoid distractions: place your phone in airplane mode, close all other windows in your computer, and try to stay focused. We will pause frequently during the session to help you regain focus. In one of the sessions, a *midterm exam* will be taken, and at the end of the course, a *final exam* will be taken. The exam questions are based exclusively on the materials shown or discussed in the lectures during class.

**After each session, there is some reading for you to do.** These readings will be much easier after you have attended each lecture, will bring depth to what you learn in class, and will help you remember these contents better. Think of these readings as a form of continuous studying that will save you time and effort when preparing for the exams.

## Session 1: Introduction

### Before class

* :tv: Watch this 6-minutes presentation of the [Knowledge Discovery in Databases](https://www.youtube.com/watch?v=0PDq4wYZqP0) process by Ali Soofastaei
* Take a look at the list of [theory topics](./),  [practice sessions](../practicum/README.md), and [evaluation rules](../upf/upf-evaluation.md)

### During class

* Lecture TT01: introduction [ppt](https://docs.google.com/presentation/d/12kqLrpH_-i2sMdwG2GjyYOtdUyYqJvp9UKC0VOERMtM/edit?usp=share_link)/[pdf](pdf/tt01_introduction_L1.pdf)
* Course overview
   * Overview of [theory topics](./)
   * Overview of [practice sessions](../practicum/README.md)
   * Overview of [evaluation rules](../upf/upf-evaluation.md)
* Lecture TT02: data, methods, and scenarios [ppt](https://docs.google.com/presentation/d/1LwJ7-TkvtY92yVhdD9xANoCoKhh9XOsQ7VJkIllC7sE/edit?usp=share_link)/[pdf](pdf/tt02_data_methods_scenarios_L1.pdf)
   * Exercise: confidence of a rule
   * Exercise: which ones are data mining tasks? (pin board)
* Lecture TT03: data preparation, data types [ppt](https://docs.google.com/presentation/d/1BerVrboqh1WiK-aRxRHSOPvbANIEVUCFywvlazWgy98/edit?usp=share_link)/[pdf](pdf/tt03_data_types_L1.pdf)
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

* Lecture TT04: data integration and cleaning [ppt](https://docs.google.com/presentation/d/142RU3QPFcS8jpw3xW8SrkwJWQQ3zSkaGW9C4qaWcHvs/edit?usp=share_link)/[pdf](pdf/tt04_integration_cleaning_L2.pdf)
   * Exercise: how to handle missing data
* Lecture TT05: data reduction and transformation [ppt](https://docs.google.com/presentation/d/1eEakhvPVe1ykQiUC2bVsjPxrwexwEYIqqzOMz-vFnDc/edit?usp=share_link)/[pdf](pdf/tt05_reduction_L2.pdf)
* Lecture TT06: similarity computation on numerical data [ppt](https://docs.google.com/presentation/d/1jzC2CbKFKnP5kxZ7EgV57otMEbKK3mj7W8THo7aftq0/edit?usp=share_linkp)/[pdf](pdf/tt06_sim_numerical_L2.pdf)
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

* Lecture TT07: similarity computation beyond numerical data [ppt](https://docs.google.com/presentation/d/1VOrirgaf0gfeMKVmuiuq0_9gKhDgGO_8etcl0GJge3E/edit?usp=share_link)/[pdf](pdf/tt07_sim_beyond_numerical_L3.pdf)
   * Exercise: compute Jaccard similarity
* Lecture TT08: finding near-duplicates [ppt](https://docs.google.com/presentation/d/1nDBeolUrQ1EIhIuJtM7FKh8CLPD0lTdY6wRI7i7lUDc/edit?usp=share_link)/[pdf](pdf/tt08_near_duplicates_L3.pdf)
   * Exercise: compute signature matrix
* Lecture TT09: locality-sensitive hashing [ppt](https://docs.google.com/presentation/d/1wT0pWcSjUSERRSom_3_ZlKqsOwfFno57mu-5opALwjM/edit?usp=share_link)/[pdf](pdf/tt09_locality_sensitive_hashing_L3_supl.pdf) [SKIPPED IN 2022 -- NOT TO BE INCLUDED IN EXAMS]

### After class

* Read the rest of chapter 3 (section 3.2.2 and following) of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* Read [chapter 3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch3n.pdf)

### Optional/additional material

* :tv: Watch this 37-minutes lecture by Ben Langmead on [Jaccard coefficient and min-hashing](https://www.youtube.com/watch?v=aTwRpqUnQX8)
* :tv: Watch Jeffrey D. Ullman, a famous computer scientist and co-author of one of the books we use in the course and of this method specifically describe this near-duplicate finding method. Two 50-minutes videos: [part 1](https://www.youtube.com/watch?v=bQAYY8INBxg), [part 2](https://www.youtube.com/watch?v=MaqNlNSY4gc).
* See presentation TT10: locality-sensitive hashing additional materials [ppt](https://docs.google.com/presentation/d/1-etsQbPafHpBvdVBeLbYDwurzk86hobBDRPTst9fVJw/edit?usp=share_link)/[pdf](pdf/tt10_locality_sensitive_hashing_additional_L3_supl.pdf)

## Session 4: Itemsets

### Before class

* :tv: Watch the first 8 minutes of this animated video [explanation of the Apriori algorithm](https://www.youtube.com/watch?v=WGlMlS_Yydk), for an explanation of the concepts of itemsets, support, confidence, and lift.

### During class

* Lecture TT11: itemsets [ppt](https://docs.google.com/presentation/d/1aLdz-eYKJrhzw42XwYKkymB63xkTRHCerVaSDrXFAG0/edit?usp=share_link)/[pdf](pdf/tt11_itemsets_L4.pdf)
   * Exercise: compute itemset support (spreadsheet)
   * Exercise: compute maximal itemsets
* Lecture TT12: association rules [ppt](https://docs.google.com/presentation/d/1PSVja43RMfkOYVS55A2ORyluHwJ0BpIESQD7UvsF73E/edit?usp=share_link)/[pdf](pdf/tt12_association_rules_L4.pdf)
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

* Lecture TT13: association rules mining [ppt](https://docs.google.com/presentation/d/1teDn5V54e0tg7dLDR_E00zvSmrseW6wOgD0wsJn2pFY/edit?usp=share_link)/[pdf](pdf/tt13_association_rules_mining_L5.pdf)
   * Exercise: prove confidence monotonicity
   * Exercise: execute Apriori algorithm (spreadsheet)
* Lecture TT14: speeding up association rules mining [ppt](https://docs.google.com/presentation/d/1fIUo99cXK7OmTc84z1FmECuuOWsPiZFSgC6jhUEu5_k/edit?usp=share_link)/[pdf](pdf/tt14_improved_rules_mining_L5.pdf)
   * Exercise: indicate which items are visited in a hash tree

### After class

* Read [section 6.2 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch6.pdf)
   * **Or** read section 4.2-4.4 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* See presentation TT15: extending association analysis [ppt](https://docs.google.com/presentation/d/1wdcg0s2UJGpc8Zu0y1aGYBQKv2ETv77gh1pFdTzPnGU/edit?usp=share_link)/[pdf](pdf/tt15_extended_association_analysis_L5_supl.pdf)
* If you did not understand well the hash tree, watch these four videos (18 minutes in total) from the J. Academy: [support counting using hash tree (part 1)](https://www.youtube.com/watch?v=qPIp3Wq64Vs), [support counting using hash tree (part 2)](https://www.youtube.com/watch?v=AIqOQA5mnGA), [hash tree generation step by step](https://www.youtube.com/watch?v=btW-uU1dhWI), [hash tree and support counting](https://www.youtube.com/watch?v=d040C7c06e4); if you find this easy to follow check their entire [playlist on association rules mining](https://www.youtube.com/playlist?list=PLk6n8LK7VfVg8r39BtrJUBrjyShlZ0nqt).

## Session 6: Mid-term exam (Wednesday October 25th, 2023)

### Before class

Study on your own TT01-TT08, TT11-TT13, try to solve exams from past years. Ask your questions in the forum.

The exam will not include TT09, TT10 or TT14.

### During class

We will have a mid-term exam, with no class after the mid-term.

## Session 7: Recommender systems

### Before class

* :tv: Watch the 6-minutes presentation of an [introduction to recommender systems](https://www.youtube.com/watch?v=U-yq3I9QugQ)
* :tv: Watch the 17-minutes [introductory lecture to recommender systems](https://www.youtube.com/watch?v=1JRrCEgiyHM) by Anand Rajaraman

### During class

* Lecture TT16: recommender systems [ppt](https://docs.google.com/presentation/d/18eMSNG-mDNMOHE1VA7Gd_JiJcHz7UDJlp8GFvIo0GoU/edit?usp=share_link)/[pdf](pdf/tt16_recommender_systems_L7.pdf)
   * Exercise: content-based single-user recommendations (spreadsheet)
* Lecture TT17: interaction-based recommender systems [ppt](https://docs.google.com/presentation/d/1A4nw83Aquqdb_KHkw_ua6_59VNKpWvV21ioPOrQ5ghQ/edit?usp=share_link)/[pdf](pdf/tt17_interaction_based_recommenders_L7.pdf)
   * Exercise: recommender based on user similarity (spreadsheet)

### After class

* Read [sections 9.1-9.3 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)
* :tv: Watch the two 21-minutes lectures on [content-based recommender systems](https://www.youtube.com/watch?v=2uxXPzm-7FY) and [collaborative filtering](https://www.youtube.com/watch?v=h9gpufJFF-0) by Anand Rajaraman

## Session 8: Recommender systems (cont.) + Outlier analysis

### Before class

* :tv: Watch the 7-minutes lecture on [outlier analysis](https://www.youtube.com/watch?v=R_XKJ_l1jBc) by Gourab Nath, discussing why outliers occur

### During class

* :tv: We will watch this 8-minutes presentation on [how recommender systems work](https://www.youtube.com/watch?v=n3RKsY2H-NE) by Art of the Problem, which describes a factorization-based (latent-factors based) method
* Lecture TT18: latent-factors based recommender systems [ppt](https://docs.google.com/presentation/d/1LgxSWBAI_eUFZh9WbIvHMFUPwDzg8J6emAxst7Y9G64/edit?usp=share_link)/[pdf](pdf/tt18_latent_factors_recommenders_L8.pdf)
* Lecture TT19: outliers introduction and extreme value analysis [ppt](https://docs.google.com/presentation/d/1fx8oy9VmyqiP00BW6PkToBkiOQDxnzCa3G_qviNk0fE/edit?usp=share_link)/[pdf](pdf/tt19_outliers_extreme_values_L8.pdf)
   * Exercise: outliers using z-score (spreadsheet)
* Lecture TT20: probability and clustering-based methods [ppt](https://docs.google.com/presentation/d/1qoqT_wnDFksfE3k_S7Moc-gClYjz1Lea3CQIVEdXNO0/edit?usp=share_link)/[pdf](pdf/tt20_outliers_probability_density_L8.pdf)
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

* Lecture TT21: density- and isolation-based methods [ppt](https://docs.google.com/presentation/d/1kmmJcywlqyn76ZqNYmbkY-gGjiR9VgqCHIH7s41-dEY/edit?usp=share_link)/[pdf](pdf/tt21_outliers_isolation_L9.pdf)
   * Exercise: isolation forest example
* Lecture TT22: data streams [ppt](https://docs.google.com/presentation/d/1bihFtSXT5xSNuliqgNhKzvYwqRDNfBrd-HNdiusPLZA/edit?usp=share_link)/[pdf](pdf/tt22_streams_L9.pdf)
   * Exercise: sampling at a fixed rate
* Lecture TT23: reservoir sampling [ppt](https://docs.google.com/presentation/d/1n1hzzkrNP3xrsOlfSWKB_3wyryX_vW4dvOC70UCPCG0/edit?usp=share_link)/[pdf](pdf/tt23_reservoir_sampling_L9.pdf)
   * Exercise: probabilities in a reservoir sample

Note for 2022 -- *need to finish outlier detection on this class* - isolation forest - for practice sessions to have the necessary background.

## After class

* Read [sections 4.1 and 4.2 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch4.pdf)
* Read section 8.5 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Optional/additional material

* Read the original ICDM 2008 [paper on isolation forests](https://scholar.google.com/scholar?cluster=11545522615192696786&hl=en&as_sdt=0,5) -- do not worry if you cannot follow all the details

## Session 10: Streams (cont.) + Time series mining

### Before class

* :tv: Watch this 3-minutes quick presentation on [bloom filters](https://www.youtube.com/watch?v=-SuTGoFYjZs) by Cube Drone

### During class

* Lecture TT24: bloom filters [ppt](https://docs.google.com/presentation/d/1a3-U9vZe6fzsx0zupA9WmLYmZ-ltR9cP4XtdSXi_Z-E/edit?usp=share_link)/[pdf](pdf/tt24_bloom_filters_L10.pdf)
   * :tv: We will watch this 6-minutes [animation on Bloom Filters](https://www.youtube.com/watch?v=kfFacplFY4Y)
* Lecture TT25: probabilistic counting [ppt](https://docs.google.com/presentation/d/1U9sIvq3pSJ0LTeBOgulgar_9n5LA2_8gBO8EZBzB87k/edit?usp=share_link)/[pdf](pdf/tt25_probabilistic_counting_L10.pdf)
   * Exercise: ideas for simple probabilistic counting
* Lecture TT27: time series [ppt](https://docs.google.com/presentation/d/1dU9f1VG9O-P7TRbmKh9LPP7vEj51xQapYLhj7j6X3ao/edit?usp=share_link)/[pdf](pdf/tt27_time_series_L10.pdf)
   * Exercise: smooth a time series (spreadsheet)

Note for 2022 -- need to finish probabilistic counting for practice session on probabilistic counting to have the necessary background

### After class

* Read [sections 4.3 and 4.4 of Mining Massive Datasets](http://infolab.stanford.edu/~ullman/mmds/ch4.pdf)
* Read sections 14.1 and 14.2 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

### Optional/additional material

* See presentation TT26: moments estimation [ppt](https://docs.google.com/presentation/d/1tdSQw5ryEdqc7TK-XWoILeXUO0tEx35NTFEjY2OuYmw/edit?usp=share_link)/[pdf](pdf/tt26_estimating_moments_L10_supl.pdf)

## Session 11: Time series mining (cont.)

### Before class

* :tv: Watch this 7-minutes talk on the [moving average model](https://www.youtube.com/watch?v=voryLhxiPzE) and this 9-minutes talk on the [autoregressive model](https://www.youtube.com/watch?v=5-2C4eO4cPQ).

### During class

* Lecture TT28: time series similarity [ppt](https://docs.google.com/presentation/d/1W_LjPLv_Qo-zGe-hj9d1I3O3yvCPhtw8ShqxNGGC1zA/edit?usp=share_link)/[pdf](pdf/tt28_time_series_similarity_L11.pdf)
   * Example: dynamic time warping (spreadsheet)
* Lecture TT29: time series forecasting [ppt](https://docs.google.com/presentation/d/1zk07T0Urs707uApRynmniui1eKEUPurDIN8jqUaCdCE/edit?usp=share_link)/[pdf](pdf/tt29_forecasting_L11.pdf)
   * Example: simple auto-regressive model (spreadsheet)

Note for 2023 -- need to finish forecasting for practice session on temperature prediction to have the necessary background

### After class

* Read section 14.3 of [Data Mining, The Textbook (2015)](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

## Final exam (Friday, December 16th, 2022)

The final exam will include recommender systems, outlier analysis, data streams, and forecasting: topics TT16-TT25, TT27-TT29; it will not include topic TT26.

# Notes

Note that session numbers are approximate and subject to change.

[<img src="../upf/cc-by-80x15.png" width="80" height="15" hspace="4"/>](https://creativecommons.org/licenses/by/4.0/) Slides available under a [Creative Commons](https://creativecommons.org/licenses/by/4.0/) license unless specified otherwise.

# Main bibliography

:blue_book: [Data Mining, The Textbook](https://www.springer.com/us/book/9783319141411) (2015) by Charu Agrawal. ISBN 978-3-319-14142-8. [Free Download](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)

:ledger: [Mining of Massive Datasets SECOND EDITION](https://www.cambridge.org/core/books/mining-of-massive-datasets/C1B37BA2CBB8361B94FDD1C6F4E47922) (2014) by Leskovec et al. ISBN 978-1107077232. Online materials: [http://www.mmds.org/](http://www.mmds.org/). [Free Download](http://infolab.stanford.edu/~ullman/mmds/bookL.pdf)

# Additional bibliography

:orange_book: [Introduction to Data Mining SECOND EDITION](https://www.pearson.com/us/higher-education/program/Tan-Introduction-to-Data-Mining-2nd-Edition/PGM214749.html) (2019) by Tan et al. ISBN 978-0-13-312890-1. Online materials: [https://www-users.cs.umn.edu/~kumar001/dmbook/index.php](https://www-users.cs.umn.edu/~kumar001/dmbook/index.php)

:blue_book: [Data Mining and Machine Learning SECOND EDITION](https://dataminingbook.info/book_html/) (2020) by Zaki and Meira. ISBN 978-1108473989.

:notebook: [Data Mining Concepts and Techniques THIRD EDITION](https://www.elsevier.com/books/data-mining-concepts-and-techniques/han/978-0-12-381479-1) (2011) by Han et al. ISBN 978-0123814791.
