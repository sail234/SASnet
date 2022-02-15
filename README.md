# SASnet
## Code
Code is put in zip file.
## Dataset
### UserBehaviorDataset
#### 1.Introduction
User Behavior is a dataset of user behaviors from Taobao, for recommendation problem with implicit feedback. The dataset is offered by Alibaba.
#### 2.Detail
random select about 1 million users who have behaviors including click, purchase, adding item to shopping cart and item favoring during November 25 to December 03, 2017. The dataset is organized in a very similar form to MovieLens-20M, i.e., each line represents a specific user-item interaction, which consists of user ID, item ID, item's category ID, behavior type and timestamp, separated by commas. 
The detailed descriptions of each field are as follows:
|  Field   | Explanation  |
|  ----  | ----  |
| User ID  | An integer, the serialized ID that represents a user |
| Item ID  | An integer, the serialized ID that represents an item |
| Category ID  | An integer, the serialized ID that represents the category which the corresponding item belongs to |
| Behavior  | A string, enum-type from ('pv', 'buy', 'cart', 'fav') |
| Timestamp | An integer, the timestamp of the behavior |

Note that the dataset contains 4 different types of behaviors, they are
|  Behavior   | Explanation  |
|  ----  | ----  |
| pv | Page view of an item's detail page, equivalent to an item click |
| buy  | Purchase an item |
| cart  | Add an item to shopping cart |
| fav  | Favor an item |

Dimensions of the dataset are
|  Dimension   | Number  |
|  ----  | ----  |
| # of pv | 987,994 |
| # of items  | 4,162,024 |
| # of categories  | 9,439 |
| # of interactions  | 100,150,807 |
#### 3.DownLoad
https://tianchi.aliyun.com/dataset/dataDetail?dataId=649

### Fliggy
#### 1.Introduction
The dataset sampled from the daily logs of online recomendation module from Mobile Fliggy APP.
#### 2.Detail
The dataset sampled from the daily users’ logs collected from April 2021 to May 2021, containing 55 user features including userID, gender, residence_city,
lbs_location, unconsumed_trip, and 22 item features including itemID, categoryID, price.

Note that the dataset contains 4 different stages of user, they are
|  Behavior   | Explanation  |
|  ----  | ----  |
| exploring | Divergent destinations & Irrelevant interactions |
| planning  | Focused destinations & correlated interactions |
| pre-trip  | Interactions related to Certaion destinations |
| on-trip  | Interactions related to local destinations |

Dimensions of the dataset are
|  Dimension   | Number  |
|  ----  | ----  |
| # of users | 2.48M|
| # of items  | 119.1K |
| # of interactions  | 37M |
#### 3.DownLoad
We are now re-processing the dataset for data masking and awaiting approval from the company. Once the procedure is complete, we will upload the dataset.
