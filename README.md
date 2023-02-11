# Russia_USAElection_Twitter

Context

As part of the House Intelligence Committee investigation into how Russia may have influenced the 2016 US Election, Twitter released the screen names of almost 3,000 Twitter accounts believed to be connected to Russia’s Internet Research Agency, a company known for operating social media troll accounts. Twitter immediately suspended these accounts, deleting their data from Twitter.com and the Twitter API. A team at NBC News including Ben Popken and EJ Fox was able to reconstruct a dataset consisting of a subset of the deleted data for their investigation and were able to show how these troll accounts went on the attack during key election moments. This dataset is the body of this open-sourced reconstruction.

For more background, read the NBC news article publicizing the release: "Twitter deleted 200,000 Russian troll tweets. Read them here."

Content

This dataset contains two CSV files. tweets.csv includes details on individual tweets, while users.csv includes details on individual accounts. The files can be joined by the filed “user_id” on the tweets.csv file and “id” on the “users.csv” file.

Guidelines In your solution, we care about the following:

Data Science process (a small part of the real world process):
a. Exploratory data analysis (EDA). b. Clean and prepare the data. c. Feature engineering. d. Model evaluation. e. Model/features explainability.

Organized code - OOP is an option but not a must, functions and clear code flow/structure will be great as well.
Versatility/depth - how deep or how versatile is your solution. Don’t try to demonstrate both, the timeframe you have is not long enough.
Any tool, algorithm, or technique used, will need to be explained.
Questions

What are the characteristics of fake tweets? a. Can you describe fake tweets topics? b. Can you recognize the emotions in those fake tweets? c. Can you understand the user’s networks involved (if any) in those fake tweets?
Are the fake tweets distinguishable from real ones? If yes, please build a supervised/unsupervised model which distinguishes between them. (you can enrich the dataset with real tweets - not a must). a. Can you leverage the knowledge/ features/ topics from the first question?
Bonus:

Can you predict ahead of time when fake tweets are going to peak?

