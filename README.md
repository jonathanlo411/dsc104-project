# DSC104 - Project
We want use a social network to show show relations and interactions between users. We will use Neo4j for this purpose. When querying for information regarding the users in the network, we will direct that to MongoDB which will hold that information. Redis will be used as a cache layer in case of duplicate queries.

## Database Systems
|Database  | Use | Data
|--|--|--|
| Redis | Cache Layer  | Raw Queries
| MongoDB | Individual Info | User Information
| Neo4j | Relationships | Social Network

## Potential Topics:
- Twitter Airlines
	- MongoDB: https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment
	- Neo4j: Loaded over Twitter API
- Yelp Reviews
	- MongoDB: https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset?select=yelp_academic_dataset_review.json
	- Neo4j: Loaded over Yelp GQL API
## Presentation Slides:
https://docs.google.com/presentation/d/1Z1MWATBhiaqORU01oEnopA2KYcKSrykfcrXBnCX_aaU/edit?usp=sharing
