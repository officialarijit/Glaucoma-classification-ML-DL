## Glaucoma and Non-Glaucoma classification using ML/Dl and ensemble approaches using Image Feature Extraction Using HOG (Histogram of Gradient)

### Packages
-   **Jupyter-Notebook** : will be used to run the programs.

    `pip install scikit-learn`

-   **Open CV** : For reading and manipulating images.

      ```pip install opencv-python```

-   **Numpy** : used for multi-dimensional arrays and matrices.

    `pip install numpy`

-   **Sklearn** : will be used to get PCA for dimensionality reduction.

    `pip install scikit-learn`

-   **Mlxtend** : will be used to implement the Majority Voting Ensemble approach. 
     
     `pip isntall mlxtend`
    
### Run The Program
- Run the program by executing the below code.


	`run Feature Extraction HOG.ipynb`

### Result
- Result is generated and placed inside the 

	`100_extracted_features.csv`.

### Classification
- Once the features are extracted then run the following code.
	`run Glaucoma-Ensemble-Approach.ipynb` 
	
	-- In this file `Multi-Layer Perceptron (MLP)`, `SVM` and `Random Forest (RF)` classifiers are available. Also, the `Majority Voting Ensemble` approach is available. 
