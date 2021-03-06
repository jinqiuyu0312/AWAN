# Environment requirement
- Anaconda3 
- pytorch 1.1.0 
- hdf5storage 
- opencv-python 

# Pre-trained models
- Download pre-trained models from [Google Drive](https://drive.google.com/drive/folders/1cn3q33tTgPaaAlYiGQ20fycxgo9m_F4s?usp=sharing).
- Then put them to the *models* folder.

# Results of validation dataset
- The validation images are in the *NTIRE2020_Validation_RealWorld* folder.
- The valid_model1.py, valid_model2.py, valid_model3.py and valid_model4.py generate the reconstructed hyperspectral images respectively.
- And then, the valid_ensemble.py will utilize the four results to generate the final results.
- The final reconstructed results are shown in the *final_valid_results* folder.
- Download the single-model results from [Single-model](https://drive.google.com/drive/folders/1mZeW3YIgOd_TID9GuW22G6DOBpR25QaT?usp=sharing)
- Download the model-ensembled results from [Model-ensembled](https://drive.google.com/drive/folders/1fJnuxSmf_SaaPYtZmrrBhSY4vH45xBbZ?usp=sharing)

# Results of test dataset
- The test images are in the *NTIRE2020_Test_RealWorld* folder.
- The test_model1.py, test_model2.py, test_model3.py and test_model4.py generate the reconstructed hyperspectral images respectively.
- And then, the test_ensemble.py will utilize the four results to generate the final results.
- The final reconstructed results are shown in the *final_test_results* folder. 
- Download the final test results from [final_test_results](https://drive.google.com/drive/folders/1YbRmZ_J_89X5PacjnyXCQ5huZjn09Nvb?usp=sharing)

# Evaluation functions
- The official scoring codes can be found [NTIRE2020_Spectral](https://github.com/boazarad/NTIRE2020_spectral).
