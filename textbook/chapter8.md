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

### Contextual modeling mehthods have been designed to explore this possibility.



