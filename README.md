Paper Tilte: "CG-Vec: Simpler is Better for Complex Magnetism Modeling."
cgcnn.ipynb: Crystal Graph Convolutional Neural Network training testing and analysis.
cgvec: Crystal graph to vector followed by ML model(Random Forest) and analysis.
computational_efficiency_tests.ipynb: compars computational efficiency of CGCNN and CG-Vec.
Interpretability.ipynb: Contains code for feature analysis (SHAP importance, impurity importance, correlations).
predict.ipynb: Contains code that demonstrate transferibility of CG-Vec model trained on datasets FM as well as FiM dataset (few trained models are present in saved models folder). 
CHGNet_benchmark.ipynb: Benchmarks CHGNet on our magnetic material dataset.

Additionally:
1. All the datasets used in the training, validations, testing as well for making predictions in presernt in "my_new_data1" folder.
2. cgvec_mapping folder contains outputs and plots of feature analysis.
3. PCA and t-SNE folder constains results for FiM materials for both CGCNN and CG-Vec.
4. cgcnn folder contains baseline CGCNN model. the code in the folder show initial feature engineering done on CGCNN (Only for better understanding CGCNN).
