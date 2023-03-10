# Diabetic-Retinopathy-Detection

<h4>Introduction</h4>

Diabetic retinopathy is a condition that may occur in people who have diabetes. It causes progressive damage to the retina, the light-sensitive lining at the back of the
eye. Diabetic retinopathy is a serious sight-threatening complication of diabetes. Diabetes interferes with the body's ability to use and store sugar (glucose). The disease is characterized by too much sugar in the blood, which can cause damage throughout the body, including the eyes. Over time, diabetes damages small blood vessels
throughout the body, including the retina. Diabetic retinopathy occurs when these tiny blood vessels leak blood and other fluids. This causes the retinal tissue to swell, resulting in cloudy or blurred vision. Diabetic retinopathy usually affects both eyes. The longer a person has diabetes, the more likely they will develop diabetic retinopathy. If left untreated, diabetic retinopathy can cause blindness.

<h4>Purpose</h4>

The goal here is to scale the doctors’ efforts through technology; to gain the ability to automatically screen images for disease and provide information on how severe the condition may be. We shall be achieving this by building a Convolutional neural network model that can automatically look at a patient's eye image and estimate the
severity of blindness in the patient. This process of automation can reduce a lot of time thereby screening the process of treating diabetic retinopathy at a large scale.

<h4>Steps</h4>

1. Load and Transform data
2. Load the Images with a generator
3. Build a 8 layer CNN model
4. Train the model MobileNetV2
5. Visualize the result
6. Class activation heatmap for image classification
