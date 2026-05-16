README - Soil Classification with ANN
Supplementary Material for Journal Submission

1. Overview
This folder contains the Simulink model, dataset, and result figures for the manuscript:
"Soil Classification Using Artificial Neural Networks in the City Center of Kütahya"

The ANN model is already trained and embedded in the Simulink file. The dataset is provided as a MATLAB .mat file.

2. MATLAB Version
Developed and tested in MATLAB R2015a.
Required Toolboxes: Neural Network Toolbox, Simulink

3. Files Included

ann_matlab_model.slx : Trained ANN Simulink model. Open and press Run to reproduce the results.
dataset.mat          : Input and target matrices saved from MATLAB workspace. 
                       Load it using: load('dataset.mat')
                       Variables inside: inputs, targets
best_validation_performance.fig : Best validation performance plot
roc.fig                         : ROC curve of the model
confusion_matrix.fig            : Confusion matrix of classification results

4. How to Run
1. Open MATLAB R2015a or later.
2. Load the dataset by running: load('dataset.mat')
3. Open 'ann_matlab_model.slx' in Simulink.
4. Press the Run button. The model will execute and display results in the workspace.
5. To view the figures, double-click the .fig files. These match the figures in the manuscript.

5. Notes
- All network weights are stored inside the .slx file.
- Simulation output should match the results reported in the manuscript (~98% accuracy).
- No additional data files or Excel files are needed.

6. Contact
For questions regarding the code and data, contact: [mail adresini buraya yaz]