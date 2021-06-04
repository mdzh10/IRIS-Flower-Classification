# IRIS-Flower-Classification
Before running all codes one has to install the following packages :
-- to install just type pip install package_name == version_no
	streamlit==0.60.0
	pandas==1.0.3
	numpy == 1.16.0
	joblib==0.14.1
	Pillow==7.1.2
	scikit_learn == 0.23.1
	matplotlib == 3.3.2
	keras == 2.4.1
	tensorflow == 2.2.0

To generate all the weights :
--run all cells of Flower_classification.ipynb

Previously genrated weights of models are
  .flower.h5 		(Neural Netowork)
  .rfc.pkl 		(random forrest classifier)
  .Knn_Classifier.pkl 	(knn classifier)

iris_app.py is the app with user interface and above mentioned weights were used for the predictions.

To run iris_app.py :
  --open cmd in the same directory as the iris_app.py
  --run streamlit run iris_app.py

this will automatically open the user interface with the default browser. Then on the left panel of the interface one has to give input values (4 features of iris flower dataset) and after that press "classify". This will show the preictions of the 3 models.

To actually check the results it is advised to use values with ground truth and those can be found in iris.csv
