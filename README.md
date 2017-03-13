# Shelter-Animal-Outcome
Kaggle competition. Multi-class problem.

A lot can be done in terms of feature engineering in this project and I have only explored a few. Here are some more ideas:
- Breed can be further explored by having more features. The 'breed2' or 'breed1/breed2' mix can be retained as opposed to being discarded. The same applies to Color. Perhaps hair length can also be an important feature (longer hair are more desirable?) which can be deducted from Breed.
- DateTime could also be a useful feature which was not used here.

Missing ages are filled using Random Forest Regressor whereas the actual multi-class prediction was done using Random Forest Classifier.
