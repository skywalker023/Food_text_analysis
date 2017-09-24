# Foodstagram ingredient analysis
Analyzing the ingredient descriptions(text) of food pics in instagram.

## Icecream example

### Distribution of ingredients
Computed distribution of ingredients(higher proportion than cutoff) in the description.
![distribution](https://github.com/skywalker023/foodstagram_ingredient_analysis/blob/master/visualization%20images/icecream_ingred_distrib.png?raw=true)
  

### Heatmap for Jensen-Shannon Divergence among countries
Computed Jensen-Shannon Divergence using ingredient distribution
![heatmap](https://github.com/skywalker023/foodstagram_ingredient_analysis/blob/master/visualization%20images/icecream_heatmap.png?raw=true)

 
### Naive bayes classifier result
![naive bayes result](https://github.com/skywalker023/foodstagram_ingredient_analysis/blob/master/visualization%20images/naive_bayes_classifier_result.png?raw=true)

* Top-1 mean accuracy: 45.35%
* Top-3 mean accuracy: 76.33%
 

### Agglomerative Hierarchical Clustering
Applied agglomerative hierarchical clustering for finding out the typical icecream.
 
![clustering](https://github.com/skywalker023/foodstagram_ingredient_analysis/blob/master/visualization%20images/icecream_agglomerative.png?raw=true)

Nicely showing the cultural difference amoung countries. More can be found in the visualization_images directory.
