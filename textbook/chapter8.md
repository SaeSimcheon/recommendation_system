# Context - Sensitive Recommendation system

- Recommendation --Tailor---> additional information that defines a situation in which recommendations are made.
- The additional information above mentioned is referred to as "context"

### Examples

#### Time

#### Location

#### Social information


### Detecting the context of a user

#### Implicit collection methods
- Little effort

##### Example
- GPS reciver
- time stamp of a customer transcation


#### Explicit collection methods
- not quite as readily available

##### Example 
- surveys or other means

#### Some others

- data mining and inference tools can be used to gather contextual information


- Traditional recommendation systems with user set $U$ and item set $I$,

-> the set of possibilities in $UxI$ is mapped to a rating
$$UxI -> rating $$


- In a context aware system, an additional set of contextual possibilities  is present in the set $C$,


- The same user might have different preferences on the context.

- The context must be included in the mapping in order to provide a more refined and accurate recommendation.

- In context sensitive recommendation systems, the possibilities in UxIxC are mapped to the ratings.

$$
h_R:U x I x C -> rating
$$



## Contextual Modeling

- In both pre and post filtering, the collaborative filtering problem is reduced to the 2-dim setting.
- The context is used in pre or post processing.
- Disadvantage 
  - context is not integrated very tightly into the recommendation algorithm. -> prevents the full use of the relationships between various user-item combinations and contexts.

#### Contextual modeling mehthods have been designed to explore this possibility.


# Q. it is difficult .. make some examples for 269 page.

### Neighborhood-based methods



### Latent Factor Models

#### In implcit feedback matrix, a unobserved entries are included as 0 in training set.
- Non-negative matrix factorization fits in implicit feedback data.
- Because of the lack of negative feedback in data, it is infeasible to drop the missing entries in the factorization model.
- It would increase the error in the unobserved entries not to set the unobserved entries as 0.

#### Factorization machine

- It can be viewed as a general tensor matrix factorization. <- check fact.

##### Basic idea
- model each rating as a linear combination of interactions between input variables.
- asscociate a k dimensional latent factor with each of the p variables obtained by flattening.
section 3.6.6.2 of chapter3


- Flatten 3 dimensional cube including users, items and contextual values into a set of rows. There are as many rows as the number of observed ratings.


##### Simple formulation

$$
\hat y = b + \sum_{i=1}^{p}\beta_i x_i + \sum_{i=1}^{p}\sum_{j=i+1}^{p}v_{i}^{T}v_jx_ix_j
$$
- 

