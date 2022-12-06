###  How to get insight from model result:


When we have built a ML model, we need to explain to senior management and non-technical stakeholders. Even for data scientist, we want to understand why the model predicts this way and why not another, for example, we need to be able to answer why the bank cannot loan to this customer?

Typically, we want to ask the following questions:

- What features in the data did the model think are most important?
- For any single prediction from a model, how did each feature in the data affect that particular prediction?
- How does each feature affect the model's predictions in a big-picture sense (what is its typical effect when considered over a large number of possible predictions)?

### Why Are These Insights Valuable?
#### These insights have many uses, including

- Debugging
- Informing feature engineering
- Directing future data collection
- Informing human decision-making
- Building trust

#### Debugging

>> The world has a lot of unreliable, disorganized and generally dirty data. You add a potential source of errors as you write preprocessing code. Add in the potential for target leakage, and it is the norm rather than the exception to have errors at some point in a real data science project. Understanding the patterns a model is finding will help you identify when those are at odds with your knowledge of the real world, and this is typically the first step in tracking down bugs.



#### Informing Feature Engineering

>> Feature engineering is usually the most effective way to improve model accuracy. Feature engineering usually involves repeatedly creating new features using transformations of your raw data or features you have previously created.

>> Sometimes you can go through this process using nothing but intuition about the underlying topic. jBut you'll need more direction when you have 100s of raw features or when you lack background knowledge about the topic you are working on.

#### Directing Future Data Collectio

>> You have no control over datasets you download online. But many businesses and organizations using data science have opportunities to expand what types of data they collect. Collecting new types of data can be expensive or inconvenient, so they only want to do this if they know it will be worthwhile. Model-based insights give you a good understanding of the value of features you currently have, which will help you reason about what new values may be most helpful.

#### Informing Human Decision-Making

>> Some decisions are made automatically by models, like credit card straignt through processing, recommendation engine. But many important decisions are made by humans. For these decisions, insights can be more valuable than predictions.


#### Building Trust

>> Many people won't assume they can trust your model for important decisions without verifying some basic facts. This is a smart precaution given the frequency of data errors. In practice, showing insights that fit their general understanding of the problem will help build trust, even among people with little deep knowledge of data science.

