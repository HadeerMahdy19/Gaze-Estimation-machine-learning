# Gaze-Estimation-machine-learning
Gaze-Estimation using machine-learning regression and mediapipe to get face landmarks<br><br>

#### ***Dataset***:
AFLW2000 image dataset<br><br>

#### ***Features***:
face keypoints extracted from Mediapipe FaceMesh Module<br><br>

#### ***Goal/Label***:
Predict (regression) Yaw, pitch and Roll for the face in the video<br><br>

#### ***Models Used***:
SVR : Best output using MultiOutputRegressor object to predict multilabels<br><br>

Separate models for each label (SVR for Yaw, Pitch, XGBoost for Roll) 

#### ***other trials include***: 
KNN , XGBoost, RandomForestTree <br><br>

#### ***Included function***:
cross validation to choose best model<br>
Grid search to find best hyperparameters<br>
centering around nose -> not used<br>
normaliztion -> not used<br>

#### ***Future Work***:
Improve separate models!
