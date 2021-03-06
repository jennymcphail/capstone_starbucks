# capstone_starbucks
Capstone project for Udacity Data Science Nano Degree, using Starbucks data. This is a pretty open ended assignment for the final project in the course. I have chosen to do some detailed analysis, followed by a predictive model. I have also tried to apply "real world" thinking to add value to the Data Science by imagining what the Marketing Department in Starbucks might want to know and how they might use any model. 
To try and demonstrate a breadth of learnings from my course, I have included:
- Visualisations
- Iterative processes
- Data Engineering
- Model building and evaluating
- A pipeline
- Model Tuning using GridSearch

# Data Sets

The data is contained in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

# Packages Used
- pandas
- numpy
- math
- json
- matplotlib
- sklearn

You can find my blog post here: [Starbucks Blog](https://github.com/jennymcphail/github.starbucks.io)
