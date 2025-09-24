# Personality-Driven-Experiences
ML Classification Case Study  ConnectSphere, a fast-growing social-wellness platform, wants to launch a revolutionary “Personality-Driven Experiences” feature. Instead of one-size-fits-all meetups and push notifications, ConnectSphere will tailor activity suggestions, in-app challenges, and social nudges based on each user’s.
Every day, users log:
Time Spent Alone (hours/day)


Comfort Level with new situations (fear stage: Yes/No)


Weekly Social Events Attended


Days Going Outdoors


Energy After Socializing (drained: Yes/No)


Size of Close-Friend Circle


Weekly Social-Media Posts


ConnectSphere’s product team believes that by predicting personality accurately, they can:
Boost Engagement: Send the right nudge at the right moment (e.g., “Small-group coffee hangout near you” versus “Friday night group dance class”).


Increase Retention: Reduce churn by suggesting events aligned with users’ social energy rhythms.


Upsell Premium: Offer targeted “Social Booster” packs—premium access to exclusive micro-events—for users most likely to buy.



Business Problem
“How can we build and validate a robust classifier that infers each user’s personality type from their in-app behavior, so that we can power hyper-personalized experiences and drive key metrics (engagement, retention, and revenue)?”
Key challenges:
No explicit personality quizzes (only behavioral signals).


Data sparsity: Some users rarely attend events or post online.


Real-time inference needs: Model must predict quickly for on-the-fly recommendations.


Measurable impact: Must tie model predictions to upticks in click-through, session length, and premium conversions.


Project Objective
Build a classification model that infers a user’s Personality (Introvert vs. Extrovert) from their behavior data. Then use that model to drive two key features:
Activity Suggestion Engine


Introverts → low-intensity, one-on-one or small-group events


Extroverts → larger social gatherings, group adventures


Engagement Nudges


E.g., “Hey, it’s been 3 days since you went outside—try our 30-minute park walk!” (for those flagged as introverted and low-activity)



Dataset & Preprocessing
Students should:
Explore & Clean


Identify any missing or extreme values.


Map “Yes”/“No” → 1/0; encode target Personality (0=Introvert, 1=Extrovert).


Feature Engineering Ideas




Modeling Tasks
Baseline classifiers


Logistic Regression [logistics regression]


K-Nearest Neighbors [ knn atomcamp]


Decision Tree [ Decision tree]
Random Forest [ Random forest] 


Hyperparameter tuning (using GridSearchCV)


LR


KNN


Decision Tree


Evaluation


Accuracy, Precision/Recall/F1


ROC-AUC


Confusion matrices


Model Selection


Compare test-set performance


Discuss trade-offs: interpretability vs. predictive power
