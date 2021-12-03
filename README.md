# Food Image Classification Dataset

Dataset for Multi-target image classification

This dataset contains a selected photographs of ready-to-consume food from different parts of world.

`food_annotated.csv` file contains the following features to enable supervised image classification:
1. `file_name` : str [unique values] - jpg image file names
2. `type` : str [`vegetarian`,`non_vegetarian`] - type of food
3. `something_sweet` : str [`present`, `not_present`] - `present` if there is sweet, dessert, fruit, sweetened drink, sweet corn, etc., and `not_present` otherwise
4. `green_leaves` : str [`present`,`not_present`] - `present` if there are green leaves and spinach, and `not_present` otherwise.

Annotations are performed manually.

`food_labels.jpg` explains data and class distribution with pie charts.
![pie](https://raw.githubusercontent.com/NandhiniPython/food/main/food_labels.jpg)
