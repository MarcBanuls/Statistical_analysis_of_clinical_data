To improve this model we can do several things:
First of all, it must be mentioned that the ICD10 columns are actually very important to make reports and analyses of clinical data.
The range of age in this report has been done arbitrarily, so we can loose information here. One good thing to do is to group the range of ages depending on the mortality to find significant differences between categories.
We can use Knn or MICE to do an imputation of the NA values in the data we are going to use. This way we can keep more data in the analyses and have better accuracy.
We scaled the values only in the NN model, but it would be prefferable to do it also in the lm and glm models.
A confusion matrix and a AUC-ROC would be great to do in the glm analysis, and study also the odds-ratio for each variable.
The NN algorithm has been seen to be of little use in this report. This NN was only to practise using this algorithm with clinical data, but I have been told that for clinical data it would be better to use supervised algorithms, like a random forest model.

Thanks to Manuel Ruiz Botella for calling me out in these subjects and giving me feedback. I will try to improve this report or create a new one more interesting when possible.
