# Finding Exoplanets

A project inspired by my personal interests.

### Description

The NASA exoplanet archive operated by Caltech, is a free resource for analyzing objects outside our solar system. Telescopes with increasingly impressive capabilities are allowing us to see deep into the universe and discover planets like Earth, that may have the conditions necessary to support life.

This notebook examines the objects in the database discovered by the Kepler Space Telescope, and attempts to create a model that can predict whether an object found is or is not an exoplanet.

In researching this, I came across a like-minded developer (Ismael Araujo) who had created a micro project on the same topic. A portion of the analysis is inspired by his work. I expounded on what Ismael had done in a couple of key ways. (1) I connected to the up-to-date dataset via the Exoplanet Archive's API. (2) I incorporated the Python library PyCaret to automate the process of model selection. (3) I evaluated the models based on a variety of metrics including accuracy, as well as precision, recall, and F1 score on both the "Yes" class and the "No" class of the target variable. I also compared performance when doing cross validation versus using the whole training set and the whole test set.

### Future analysis

Next steps: Perform hyperparameter tuning on the models to improve accuracy.

