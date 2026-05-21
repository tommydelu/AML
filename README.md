# Project
- Advanced Machine Learning
- University of Verona
- Accademic year 2025-2026
- Lectured by Dr. Wang

# Aim of the project
5 way 5 shot learning
A training set consisting in 5000 images is given
A test set consisting in 20 episodes, with 50 images each (25 support, 25 query) is given
The test metrics are computed by the Kaggle platform on the query images, after submitting the csv containing id_query_img + label predicted

# Sketch of the scheduling
1) Visualize data and extract some info (resolution, classe....), to have an idea of the dataset
2) try a state of the art model on the test dataset, pre-trained and not fine tuned.
3) try a pre-trained state of the art model but fine tuned on the train dataset --> see if accuracy improves
4) Data augmentation
5) collect results, with different hyper parameters
6) visualize plots of the results, make some benchmarks...
7) Sam augmentation could be a possibility, see if it works
