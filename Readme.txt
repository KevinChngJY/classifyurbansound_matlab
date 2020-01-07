<h1>Overview :</h1>
            
The credits for this example go to Ian Alfred. He drafted this example, I modified the example to explain my insight and solution. For this example, we are going to classify Urban sounds dataset using Machine Learning. Please be take note, i would not explain deep learning technique, although people generally believe deep learning technique could get higher accuracy. Let see what can we do with Machine Learning first. For this project we will use a dataset called Urbansound8K. The dataset contains 8732 sound excerpts (<=4s) of urban sounds from 10 classes, which are:
            
Air Conditioner
Car Horn
Children Playing
Dog bark
Drilling
Engine Idling
Gun Shot
Jackhammer
Siren
Street Music

The accompanying metadata contains a unique ID for each sound excerpt along with it's given class name. A sample of this dataset is included with the accompanying git repo and the full dataset can be downloaded from here.    
            
            There are 7 milestones in this example :
            
Milestone 1 : Introduction to the Example, Explore and Visualize the Data
Milestone 2 : Data Pre-processing and Extracting Features using Diagnostic App Designer (Signal Time-Domain Features & Spectral Features)
Milestone 3 : Model Training and Evaluation
Milestone 4 : Model Deployment
Milestone 5 : Extract Feature using MFCC to train Machine Learning Model
Milestone 6 : Classify Urban Sound using Wavelet Analysis and Deep Learning

Highlights : 
preparing the real life data for audiodatastore
Standardize and normalize the digital signal data (Sample Rate, Bit-Depth, Number of Channel)
Extract features with different approaches (Time-domain Signal features & Spectral Features, MFCC, Discrete Wavelet Transform, Haar 1D Wavelet Transform)
Train machine learning model using classification learner app
Train deep learning model
deploy machine learning model to embedded devices or desktop application

Product Focus :
MATLAB
Audio Toobox
Statistics and Machine Learning Toolbox
Signal Processing Toolbox
DSP System Toolbox
Wavelet Toolbox
Deep Learning Toolbox
