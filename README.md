# Healthy-and-Faulty-Audio-Model
This notebook is meant to be runned to convert audio files into MFCC features and predict wether they are Healthy or Faulty.
## Requirements
- To run the notebook type the following commands:
	- ```pip install librosa```
	- ```pip install seaborn```
- Once you've trained the SVM model run the following commands to save it:
	- ```filename = '.\Pickle\SVM-model-Healthy-Faulty-Audios.pkl'```
	- ```pickle.dump(svclassifier,  open(filename, 'wb'))```

You can save the ```filename``` path adding a point at the beginning (```'..\Pickle\SVM-model-Healthy-Faulty-Audios.pkl'```) to use it in the model deployment application


