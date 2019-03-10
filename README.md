# Text Analytics - Propose New Yelp Webpage Design

This project is intended to propose a new webpage design for businesses and reviewers on Yelp with this new design driven by analytics metrics. 

Work is based on the Yelp dataset available at https://www.yelp.com/dataset_challenge 

A- Design:
- (MongoDB) Based on your understanding of the Yelp setup, design a pseudo database schema for MongoDB. Provide all appropriate indexes and constraints. Don’t be limited to the dataset format and content.
- (Neo4j) Design a pseudo database schema for Neo4j to account for businesses, users and reviews.
- Report both design and include a detailed description of your design as well as the rationale/ justification.

B- Basic understanding of the data (12pts):
- (MongoDB) You are asked to provide an overview of the database. To do so, questions you might want to answer (among others) are: what is the overall number of businesses, the overall number of reviews, the overall number of reviewers, the overall number of reviews with ratings less than 3, the overall number of reviews with ratings more than 3, the average number of reviews per business, the date of the first review per category, the top 10 most prolific reviewers, the top 10 most verbose reviewers...
- Report and interpret your findings (e.g., if you find that there are more positive (>3) reviews than negative (<3), what implication does that have?, is the trend the same across businesses types? What about restaurants?)

C- Analytics (32pts)
You are asked to prepare a variety of analytics metrics that would be useful to include on Yelp's webpages.
- (MongoDB) Propose a list of no less than 5 metrics (such as review histogram, list of top 10 most recent reviews, list of top 10 most prolific reviewers...). Justify your choice and implement the needed queries.
- (MongoDB) The issue of identifying the helpfulness of reviews is always tricky. Propose and derive a text-based and a non-text based definition. Run the queries and derive the results for both. Are the text-based and the non-text based approaches in agreement on results? Why so?
- (Neo4j) Reviewers sometimes review as a mob (reviewing the same set of businesses over and over). Do you find this behavior in this dataset? Run the queries and derive the results.

- (Neo4j) Does geographical proximity leads to uniformity in business ratings or divergence? Run the queries and derive the results. Explain your findings.
- (SAS) The issue of identifying fake reviews is always tricky. Propose and derive a text-based definition and run the needed analysis. Explain your findings.


D- Design (16pts)
- Based on the previous analysis, design the front page of Yelp for a given business and for a given reviewer. Your design should look like a template for a business webpage on Yelp and a reviewer webpage on Yelp that shows what analytics metrics you will be featuring on those webpages.

