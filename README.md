# coursereviews-automl
training Google AutoML model for student course reviews using 2017 Kaggle 100K Coursera's Course Reviews Dataset 


The steps that you need to train Google AutoMl model for course reviews is as follows:

1) setup a [google cloud](http://cloud.google.com) account 
2) read the beginner's guide to using AutoMl for natural language at [https://cloud.google.com/natural-language/automl/docs/beginners-guide](https://cloud.google.com/natural-language/automl/docs/beginners-guide)
3) download [Kaggle 100K Coursera's Course Reviews Dataset](https://www.kaggle.com/septa97/100k-courseras-course-reviews-dataset) or access the data set from folder with the same name inside the repo
4) read the instructions on [preparing your training data](https://cloud.google.com/natural-language/automl/docs/prepare)
5) setup a google cloud project for AutoML and a google cloud storage for the dataset. [quickstart](https://cloud.google.com/natural-language/automl/docs/quickstart) is useful here. 
6) setup the dataset and manage the model. You can do this via the ui at [https://cloud.google.com/automl/ui/](https://cloud.google.com/automl/ui/) or through Python/Java/command line/nodejs as explained in [https://cloud.google.com/natural-language/automl/docs/models#automl-nl-example-web](https://cloud.google.com/natural-language/automl/docs/models#automl-nl-example-web)
My code is listed in coursera-reviews.ipynb as a Jupyter notebook

7) check the results and validate your dataset through the AutoML UI listed in 6

Now that you have the model trained and validated, you can evaluate the model with new data
