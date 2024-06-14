# ANALYZING AND MITIGATING CUSTOMER CHURN AT MODEL FITNESS: A DATA-DRIVEN STRATEGY
# Data
datasets/gym_churn_us.csv:
> - Churn — the fact of churn for the month in question
> - gender
> - Near_Location — whether the user lives or works in the neighborhood where the gym is located
> - Partner — whether the user is an employee of a partner company (the gym has partner companies whose employees get discounts; in those cases the gym stores information on customers' employers)
> - Promo_friends — whether the user originally signed up through a "bring a friend" offer (they used a friend's promo code when paying for their first membership)
> - Phone' — whether the user provided their phone number
> - Age
> - Lifetime — the time (in months) since the customer first came to the gym
> - Contract_period — 1 month, 3 months, 6 months, or 1 year
> - Month_to_end_contract — the months remaining until the contract expires
> - Group_visits — whether the user takes part in group sessions
> - Avg_class_frequency_total — average frequency of visits per week over the customer's lifetime
> - Avg_class_frequency_current_month — average frequency of visits per week over the current month
> - Avg_additional_charges_total — the total amount of money spent on other gym services: cafe, athletic goods, cosmetics, massages, etc.

# Goal
> - Develop an accurate model to predict the likelihood of each customer discontinuing their gym membership within the upcoming month.
> - Create distinct profiles for different customer groups by analyzing their activity patterns, preferences, and demographics to understand better who is most at risk of churn.
> - Leverage the insights gained from the data to recommend specific, actionable strategies aimed at reducing churn rates and improving overall customer engagement and satisfaction

# Libraries
> - *pandas ,matplotlib ,numpy, seaborn, nltk, scipy, plotly.express, proportions_ztest*
> - *scikit-learn (sklearn)* : model_selection.train_test_split, preprocessing.StandardScaler, linear_model.LogisticRegression, ensemble.RandomForestClassifier, cluster.KMeans, metrics.accuracy_score, metrics.precision_score, metrics.recall_score, metrics.f1_score, metrics.roc_auc_score
> - *scipy*: cluster.hierarchy.dendrogram, cluster.hierarchy.linkage
