# "Shit My Reviewers Say" Data Set

Data set of 780 unique quotes collected from the ShitMyReviewersSay Tumblr blog (source: https://shitmyreviewerssay.tumblr.com/).

All quotes have been labeled with either one of the following categories:

- `unprofessional`: The reviewer's comment is unprofessional, impolite or excessively harsh.
- `unconstructive`: The reviewer's comment is unconstructive or very vague.

Certain quotes were duplicated or irrelevant and are removed from the dataset. Additionally, some quotes referred to
English errors in papers but themselves contained English errors. Since these examples are evidently posted for irony,
they are discarded from the dataset. This is because vector representations of similar comments without such English
errors may be semantically very close. As the data set may use for training a model to detect unprofessional or
unconstructive comments, it is important to avoid such examples.

Labelling was performed by Dietrich Rordorf, 2023 as part of a Master's thesis at the University of Applied Sciences
Northwestern Switzerland (FHNW).
