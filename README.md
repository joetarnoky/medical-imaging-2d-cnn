# medical-imaging-2d-cnn

**Medical Imaging CNN for Organ Deformation Prediction**

This project uses a convolutional neural network to predict organ deformation in radiotherapy from CT scan data. It was developed as part of my master’s research at the University of Manchester.

**Overview**

The goal of the project was to explore whether deep learning could be used to automate organ deformation prediction in a medical imaging setting. The model was trained on CT scan data and evaluated using statistical performance measures.

**Methods**
- Built a convolutional neural network in TensorFlow.
- Prepared CT scan data by slicing 3D scans and using data from the resultant 2D scans as training data.
- Improved model performance through preprocessing and architectural changes.
- Evaluated predictions using the Pearson correlation coefficient.

**Results**
- Uncovered a source of significant overtraining resulting in inflated performane metrics.
- Once this source of overtraining had been removed, we improved Pearson coefficient from 0.14 to 0.82.
