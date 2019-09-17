# <img src="upf_logo.png" align="right" width="80"/>24933 – Mining of Massive Datasets

Course presentation for the 2019 edition.

## Presentation

Finding patterns in large datasets is one of the main tasks that a data scientist performs professionally. Data mining sits at the intersection of databases and statistics, and includes several steps from managing to pre-processing, cleaning, modeling, and performing inferences using data.

Data mining can be a challenging task. Data may not be formatted ideally for a purpose, or it may include noisy or missing data points. Datasets can be extremely large making even quadratic-time algorithms impractical. In many cases, the size of a dataset is unbounded and one needs to provide answers as new data elements keep arriving.

This course offers the students the possibility of learning fundamental data mining algorithms.

## Associated competences

**Basic competences**

CB3. That the students have the ability of collecting and interpreting relevant data (normally within their study area) to issue judgements which include a reflection about relevant topics of social, scientific or ethical nature.

**Transversal competences**

CT3. Applying with flexibility and creativity the acquired knowledge and adapting it to new contexts and situations.

**Specific competences**

RA.CE7.2 Recognizing the statistic techniques applied to data mining.

RA.CE9.2 Recognizing and applying data mining techniques.

## Results from learning

At the end of the course, the students would have acquired:

* Knowledge of typical data mining pipelines.
* Techniques for pre-processing data.
* Knowledge of similarity metrics.
* Techniques for fast similarity searches.
* Knowledge of basket analysis basics.
* Methods for association rules mining.
* Knowledge of recommender systems basics.
* Methods for creating recommender systems.
* Knowledge of the streaming data model.
* Methods for handling data streams and time series.

## Requirements

The course requires:

1. Skills in programming and data structures.
2. Basic knowledge of statistics.
3. Skills in machine learning methods.

The practical part of the course will be delivered in Python, hence it is strongly recommended to have a background in Python.

## Contents

There are 12 theory topics (TT01-TT12) in this course.

* TT01 Introduction to Data Mining
    * Data mining scenarios
    * Data types
    * Methods overview
    * Challenges overview
* TT02 Data preparation
    * Data type conversions
    * Data cleaning
    * Sampling
    * Data reduction
* TT03 Similarity
    * Data types and similarity
    * Lp norm
    * Distances and orientation
    * Local variations
* TT04 Near duplicates
    * Shingling
    * Min-hash
    * Locality-sensitive hashing
* TT05 Itemsets
    * Transaction and itemset
    * Maximal and closed itemsets
    * Association rules
    * Support, confidence, lift
* TT06 Association rule mining
    * A priori algorithm
    * Interesting patterns
* TT07 Extending association analysis
    * Interestingness measures
    * Categorical and continuous attributes
    * Min-Apriori
    * Mining rules on a hierarchy
* TT08 Recommender systems
    * Content-based recommendations
    * Interaction-based recommendations (user-based, item-based)
    * Latent factors methods
    * Evaluation
* TT09 Outlier analysis
    * Extreme values analysis
    * Isolation forest
    * Clustering-based methods
    * Distance-based methods
    * Density-based methods
    * Outlier validity
* TT10 Streams
    * Load shedding
    * Sampling (fixed proportion)
    * Sampling (fixed size)
    * Bloom filters
    * Probabilistic counting
    * Moments
* TT11 Time series mining
    * Series preparation (interpolation, smoothing)
    * Dynamic time warping
    * Time series forecasting
    * Event detection
* TT12 Spectral graph clustering
    * Graph projections

## Methodology

The course is structured around theory classes in which the topics of the course are introduced.

In seminar and practice sessions, students can work individually or in small groups in performing network analysis tasks. At the end of each session, each student reports his/her findings individually with a 1-2 pages report.

There are three group projects (groups of two students), which integrate the techniques seen in the seminar sessions. These are accompanied by practice sessions for instructors to solve student questions regarding these projects.

# Evaluation

See [evaluation rules](upf-evaluation.md)

# Bibliography

* [Data Mining, The Textbook](https://www.springer.com/us/book/9783319141411) (2015) by Charu Agrawal. ISBN 978-3-319-14142-8. [Free Download](https://doc.lagout.org/Others/Data%20Mining/Data%20Mining_%20The%20Textbook%20%5BAggarwal%202015-04-14%5D.pdf)
* [Mining of Massive Datasets SECOND EDITION](https://www.cambridge.org/core/books/mining-of-massive-datasets/C1B37BA2CBB8361B94FDD1C6F4E47922) (2014) by Leskovec et al. ISBN 978-1107077232. Online materials: [http://www.mmds.org/](http://www.mmds.org/). [Free Download](http://infolab.stanford.edu/~ullman/mmds/bookL.pdf)
* [Introduction to Data Mining SECOND EDITION](https://www.pearson.com/us/higher-education/program/Tan-Introduction-to-Data-Mining-2nd-Edition/PGM214749.html) (2019) by Tan et al. ISBN 978-0-13-312890-1. Online materials: [https://www-users.cs.umn.edu/~kumar001/dmbook/index.php](https://www-users.cs.umn.edu/~kumar001/dmbook/index.php)
* [Data Mining Concepts and Techniques THIRD EDITION](https://www.elsevier.com/books/data-mining-concepts-and-techniques/han/978-0-12-381479-1) (2011) by Han et al. ISBN 978-0123814791.
