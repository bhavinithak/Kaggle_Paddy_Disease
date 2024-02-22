Kaggle Paddy Doctor: Paddy Disease Classification [Link](https://www.kaggle.com/competitions/paddy-disease-classification/overview)
=================================================

Best Submission
---------------
Convnext_small_in22k model with Scaleup, squish, and test time augmentation (Kaggle Score: 0.97926)


Model Iterations
----------------
- Resnet26d (error_rate:0.128304)
- Convnext_small_in22k (error_rate: 0.035560)

Preprocessing Iterations
-------------------------
- Resize squish (error_rate: 0.035560)
- Resize crop (error_rate: 0.044210)
- Resize padding with zeros (error_rate: 0.038443)
- Scaleup and squish (error_rate: 0.021144)
- Test time augmentation (error_rate: 0.0197)
