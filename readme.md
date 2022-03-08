# Recommendation system study
## papers
### About topic
- Zhang et al. Deep learning based recommender system: A survey and new perspectives. ACM Comput.Surv, 2018.
- Zhang et al. Explainable Recommendation: A Survey and New Perspectives. arXiv, 2018.
- Sriharsha et al. A Survey on Group Recommender Systems. J. Intell. Inf. Syst., 2019.
- Shoujin et al. A Survey on Session-based Recommender Systems. arXiv, 2019.
- Shoujin et al. Sequential Recommender Systems: Challenges, Progress and Prospects. IJCAI, 2019.

### In statistical approach and data mining

To January 08 2022, make a list of recommendation system paers.
From these perspectives,
- No deep learning.
- Several topics can be considered.

At 14:00 January 12 2022, topic and paper might be fixed.
When I find a good paper, upload the paper on google drive shared with professor.

### 0111 search

0. Context-aware -> textbook
- factorization machine
- tensor factorization includes matrix factorization

1. Advanced Factorization machine

  - A Location-Based Factorization Machine Model for Web Service QoS Prediction
  - DiFacto — Distributed Factorization Machines
  - Liu, C., Zhang, T., Li, J., Yin, J., Zhao, P., Sun, J., & Hoi, S. C. (2019, May). Robust Factorization Machine: A Doubly Capped Norms Minimization. In Proceedings of the 2019 SIAM International Conference on Data Mining (pp. 738-746). Society for Industrial and Applied Mathematics.



3. clustering -> recommendation in each group-(clustering based recommendation system)
  - textbook -> **references** -> "The main problem with neighborhood-based methods is **the complexity of the offline phase**,
which can be quite significant when the number of users or the number of items is very large."
    - S. Chee, J. Han, and K. Wang. Rectree: An efficient collaborative filtering method.
    Data Warehousing and Knowledge Discovery, pp. 141–151, 2001.

    - M. O’Connor and J. Herlocker. Clustering items for collaborative filtering. Proceedings
    of the ACM SIGIR workshop on recommender systems, Vol 128. 1999.

    - B. Sarwar, G. Karypis, J. Konstan, and J. Riedl. Recommender systems for largescale
    e-commerce: Scalable neighborhood formation using clustering. International
    Conference on Computer and Information Technology, 2002.

    - G. Xue, C. Lin, Q. Yang, W. Xi, H. Zeng, Y. Yu, and Z. Chen. Scalable collaborative
    filtering using cluster-based smoothing. ACM SIGIR Conference, pp. 114–121, 2005.

    - B. Xu, J. Bu, C. Chen, and D. Cai. An exploration of improving collaborative recommender
    systems via user-item subgroups. World Wide Web Conference, pp. 21–30, 2012.
      - Scalable and interpretable product recommendations via overlapping co-clustering
      - Simultaneous co-clustering and learning to address the cold start problem in recommender systems
        - **coclustering**
          - **A novel Collaborative Filtering recommendation approach based on Soft Co-Clustering**

 - Opinions :
  - **multiple disciplines based on cluster for hybrid recommendation system? or multi-regime recommendation system?**
  
  - **clustering ensemble based recommendation system?**
  
    **-> Cluster ensembles in collaborative filtering recommendation**
  - **OR multi clustering recommendation**
  
4. Low computing cost -> scalable
  - cost effective -> **invalid**
  - scalable
7. multiple disciplines based on cluster

2. Group 

5. HMM

6. statistical approach


- A list of pages which are worth reading.
  - Codes given by LDJ cto class.
  - [Getting Started with a Movie Recommendation System](https://www.kaggle.com/ibtesama/getting-started-with-a-movie-recommendation-system)
  - [A Detailed Explanation of Keras Embedding Layer](https://www.kaggle.com/rajmehra03/a-detailed-explanation-of-keras-embedding-layer)
  - [CF Based RecSys by Low Rank Matrix Factorization](https://www.kaggle.com/rajmehra03/cf-based-recsys-by-low-rank-matrix-factorization#5-\)-Using-a-Neural-Network)
  - [A Detailed Explanation of Keras Embedding Layer](https://www.kaggle.com/rajmehra03/a-detailed-explanation-of-keras-embedding-layer)
  - [Collaborative Filtering for Movie Recommendations](https://keras.io/examples/structured_data/collaborative_filtering_movielens/)
  - [DeepFM](https://github.com/ChenglongChen/tensorflow-DeepFM)
  - [NFM](https://github.com/hexiangnan/neural_factorization_machine)
  - [DeepCTR](https://github.com/shenweichen/DeepCTR)
  - [A Transformer-based recommendation system](https://keras.io/examples/structured_data/movielens_recommendations_transformers/)

## Algorithm

- User based collaborative filtering
- Item based collaborative filtering
- Matrix factorization
  - [Nonnegative matrix factorization](https://scikit-learn.org/stable/modules/decomposition.html#nmf)
    - [Digest](https://angeloyeo.github.io/2020/10/15/NMF.html)
    - [Example](https://github.com/nicolasfguillaume/Recommender-Systems-Making-Movies-Recommendation/blob/master/MovieLens%20(NMF)%20v1.ipynb)


## Key words 

- scalable, cost-effective, clustering-based, extensible, cold start, hybrid, ensemble, extensible, implicit, time aware
