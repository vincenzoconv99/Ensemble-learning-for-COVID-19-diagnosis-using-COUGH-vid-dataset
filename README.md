# Ensemble-learning-for-COVID-19-diagnosis-using-COUGH-vid-dataset

This work is based on the publicly-available COUGH-vid dataset, which is considered to be the largest COVID-19 audio dataset.
We compared many classifiers and stacked them to have more robust predictions for the COVID-19 diagnosis task.

<ul>

<li>
  <b>0_convert.ipynb</b> contains the code used to convert to waw other audio format files.
</li>
  
<li>
  <b>1_data_exploration.ipynb</b> data exploration on the dataset
</li>

<li>
  <b>2_segmentation_featureextraction.ipynb</b> used to segment audio in multiple cough segments and extract features
</li>

<li>
  <b>3_pca_and_kmeans_on_the_selected_feature_subset.ipynb</b> used to understand the problem difficulty by applying pca and then K-means to see how many samples it cluster correctly.
</li>

<li>
  <b>4_ensemble_learning.ipynb</b> used to learn single classifiers and stack them
</li>

<li>
  <b>5_classifiers_comparison.ipynb </b> used to understand how similar classifiers are
</li>

  
</ul>
