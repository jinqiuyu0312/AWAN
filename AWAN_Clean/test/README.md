# Environment requirement
- Anaconda3 
- pytorch 1.1.0 
- hdf5storage 
- opencv-python 

# Pre-trained models
- Download pre-trained models from [Google Drive](https://drive.google.com/drive/folders/1njWoW5PmJVvLGbV362ioucOk0OEhjkAJ?usp=sharing).
- Then put them to the *models* folder.

# Results of validation dataset
- The validation images are in the *NTIRE2020_Validation_Clean* folder.
- The valid_model1.py, valid_model2.py, valid_model3.py and valid_model4.py generate the reconstructed hyperspectral images respectively.
- And then, the valid_ensemble.py will utilize the four results to generate the final results.
- The final reconstructed results are shown in the *final_valid_results* folder.
- Download the single-model results from [Single-model](https://drive.google.com/drive/folders/1Hhu6f-0otFTHoITItBdPPvhk3w2N9YEA?usp=sharing)
- Download the model-ensembled results from [Model-ensembled](https://drive.google.com/drive/folders/1iKOa3pn89WfyG2bjQZK76t9JhGmcPec2?usp=sharing)

# Results of test dataset
- The test images are in the *NTIRE2020_Test_Clean* folder.
- The test_model1.py, test_model2.py, test_model3.py and test_model4.py generate the reconstructed hyperspectral images respectively.
- And then, the test_ensemble.py will utilize the four results to generate the final results.
- The final reconstructed results are shown in the *final_test_results* folder.
- Download the final test results from [final_test_results](https://drive.google.com/drive/folders/1O1yu4zBQmrASnBzSnLAJNUqOqvZi1TeQ?usp=sharing)

# Evaluation functions
- The official scoring codes can be found [NTIRE2020_Spectral](https://github.com/boazarad/NTIRE2020_spectral).
