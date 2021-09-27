# Ventilator Pressure Prediction using EDA + DL




What do doctors do when a patient has trouble breathing? They use a ventilator to pump oxygen into a sedated patient's lungs via a tube in the windpipe. But mechanical ventilation is a clinician-intensive procedure, a limitation that was prominently on display during the early days of the COVID-19 pandemic. At the same time, developing new methods for controlling mechanical ventilators is prohibitively expensive, even before reaching clinical trials. High-quality simulators could reduce this barrier.

<img src="https://raw.githubusercontent.com/google/deluca-lung/main/assets/2020-10-02%20Ventilator%20diagram.svg" width="600px">

* Link Project

[![Here]](https://www.kaggle.com/yasserhessein/ventilator-pressure-prediction-using-eda-dl)


* Link video

[![Here]](https://www.youtube.com/watch?v=jNL8Iyhvx3o)

### Files
* train.csv - the training set
* test.csv - the test set
* sample_submission.csv - a sample submission file in the correct format


### Columns
* id - globally-unique time step identifier across an entire file
* breath_id - globally-unique time step for breaths
* R - lung attribute indicating how restricted the airway is (in cmH2O/L/S). Physically, this is the change in pressure per change in flow (air volume per time). Intuitively, one can imagine blowing up a balloon through a straw. We can change R by changing the diameter of the straw, with higher R being harder to blow.
* lung attribute indicating how compliant the lung is (in mL/cmH2O). Physically, this is the change in volume per change in pressure. Intuitively, one can imagine the same balloon example. We can change C by changing the thickness of the balloon’s latex, with higher C having thinner latex and easier to blow.
* time_step - the actual time stamp.
* u_in - the control input for the inspiratory solenoid valve. Ranges from 0 to 100.
* u_out - the control input for the exploratory solenoid valve. Either 0 or 1.
* pressure - the airway pressure measured in the respiratory circuit, measured in cmH2O.

### 
Dataset link 

[Here](https://www.kaggle.com/c/ventilator-pressure-prediction/overview)


Ventilator Pressure Prediction using EDA + DL by Yasir Hussein Shakir


* version 0.0.4
* 28-9-2021
* How to reach me ?
* Emails:
* Uniten : pe20911@uniten.edu.my
* Yahoo : yasserhesseinshakir@yahoo.com
* Kaggle : https://www.kaggle.com/yasserhessein
* GitHub : https://github.com/yasserhessein
* linkedin : https://www.linkedin.com/in/yasir-hus...
* Source :

 https://keras.com
 
 https://tensorflow.com
 
 https://pypi.org/project/dataprep/

