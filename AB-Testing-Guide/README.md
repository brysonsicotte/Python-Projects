# A/B Testing Guide

This guide walks through the basic steps of creating an A/B test, and then drawing conclusions using correct statistical principles.

For this guide we will use a dataset from Kaggle. https://www.kaggle.com/datasets/zhangluyuan/ab-testing?select=ab_data.csv The dataset contains records of website users, whether they visited the old or new version of the website, and whether or not they converted. In this hypothetical scenario, let us assume that best efforts have been made to control for external factors. To provide some examples, let us assume the users are from the same season, same days during the month, and that the date range avoids anomalous days such as holidays, and days when special promotions are running.

This was produced as part of a code-along of an A/B testing guide created by Github user "renatofillinich". Alterations have been made to the original source material.

https://github.com/renatofillinich/ab_test_guide_in_python/blob/master/AB%20testing%20with%20Python.ipynb
