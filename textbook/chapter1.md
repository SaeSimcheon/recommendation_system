




# 1.3 Basic Models of Recommendation systems
## Two kinds of data for models of recommendation systems
### User-Item interactions
- ratings
- buying behavior

### Attribute information about users and items
- textual profiles
- relevant keywords

## Former -> Collaborative filtering and Latter -> Content based recommender

## Do Content based systems use the ratings matrices?
### -> focus on the ratings of a single user than all users.


## Knowledge based recommender systems
### External knowledge bases and contraints are used <-> user historical rating or buying
### Explicitly specified requirements users give <-> user historical rating or buying

## Hybrid systems

### Combine different aspects -> combine the strengths of various types of recommender systems to create techniques performing robustly in various settings.


# 1.3.1 Collaborative filtering

## Basic idea
### Assumption
- The observed ratings are often highly correlated across various users and items.
### Unspecified ratings are imputable.
### Example
  1. There are some users who have similiar tastes.
  2. The values which all users specify are similar
  3. The similarity is identified by underlyting algorithm.
  4. similarity can be user to predict the unspecified values.

### Most of CFs focus on using item-item similarity or user-user similarity for predicting.


## Memory-based collaborative filtering -> make presentation slides
- also referred to as neighborhood based collaborative filtering
- the ratings are imputed based on neighborhoods.

### User based collaborative filtering
- Determine users who are similar to the target user, 
- and then recommend ratings for the unobserved ratings of the user by computing weighted averages of the ratings of peer group.
#### Use the ratings of members in peer group of the target user and Weight the values through similarities of users to target user.

### Item based collaborative filtering
- Make the raing prediction for a target item by a user.
- Determine a set of items that are similar to the target item.
- The ratings in the set and specified by the user are used to predict whether the user will love the target item.
#### Use the target user's ratings and Weight the values through similarities of items to target item.


### Advantages
- simple to use
- explainable

### Disadvantages
- Bad performance on sparse matrix. -> lack coverage.
- Heuristic
## Model based collaborative filtering
- ML and DM methods are used as predictive models.
- Decision trees, rule-based models, Bayesian methods and latent factor models.
- Many of them have a good coverage for sparse ratings matrices.


## Distinction is artificaial -> memory-based can be viewed as similarity based methods.



## 1.3.1 Types of rating

- Recommendation algorithm design <- influence <- sytem for tracking ratings.
- 
