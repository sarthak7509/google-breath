# Google Brain - Ventilator Pressure Prediction(https://www.kaggle.com/c/ventilator-pressure-prediction)
What do doctors do when a patient has trouble breathing? They use a ventilator to pump oxygen into a sedated patient's lungs via a tube in the windpipe. But mechanical ventilation is a clinician-intensive procedure, a limitation that was prominently on display during the early days of the COVID-19 pandemic. At the same time, developing new methods for controlling mechanical ventilators is prohibitively expensive, even before reaching clinical trials. High-quality simulators could reduce this barrier.

Current simulators are trained as an ensemble, where each model simulates a single lung setting. However, lungs and their attributes form a continuous space, so a parametric approach must be explored that would consider the differences in patient lungs.

Partnering with Princeton University, the team at Google Brain aims to grow the community around machine learning for mechanical ventilation control. They believe that neural networks and deep learning can better generalize across lungs with varying characteristics than the current industry standard of PID controllers.

In this competition, you’ll simulate a ventilator connected to a sedated patient's lung. The best submissions will take lung attributes compliance and resistance into account.

If successful, you'll help overcome the cost barrier of developing new methods for controlling mechanical ventilators. This will pave the way for algorithms that adapt to patients and reduce the burden on clinicians during these novel times and beyond. As a result, ventilator treatments may become more widely available to help patients breathe.

## Implementations
1. This repository contains the code of the pressure prediction using Bidirectional LSTM
2. With the KFold validation and a simple time frame of 80.
3. This implmentation shows or represents that a task like pressure, heart beat or any human motion is time dependant and previous patter possibly be helpful to predict the next motion.
4. Requirements to run this notebook is given below<br>
``` python  
pip install requirements.txt
```
5. This notebook scored 0.464
6. current notebook score is 0.311(all notebook will be released at the end of the competition)