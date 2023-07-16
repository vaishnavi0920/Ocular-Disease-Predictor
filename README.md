Ocular-Disease-Predictor
Introduction
Early ocular disease detection is an economic and effective way to prevent blindness caused by diabetes, glaucoma, cataract, and many other diseases. According to World Health Organization (WHO) at present, at least 2.2 billion people around the world have vision impairments, of whom at least 1 billion have a vision impairment that could have been prevented. Rapid and automatic detection of diseases is critical and urgent in reducing the ophthalmologist’s workload and prevents vision damage of patients. Computer vision and deep learning can automatically detect ocular diseases after providing high-quality medical eye fundus images. Rapid and automatic detection of diseases is critical and urgent in reducing the ophthalmologist's workload.

About Dataset
The dataset consists of Normal, Diabetic Retinopathy, Cataract and Glaucoma retinal images where each class have approximately 1000 images. These images are collected from various sorces like IDRiD, Oculur recognition, HRF etc.

Diabetic retinopathy: The persistently high blood sugar levels that occur with diabetes can damage the retina’s small blood vessels (capillaries), which deliver oxygen and nutrients. Diabetic retinopathy affects up to a third of people with diabetes over the age of 502.

Cataracts: A cataract is a clouding of the lens in the eye. Left untreated, cataracts can eventually lead to blindness. People with diabetes are more likely to develop cataracts at an earlier age and suffer visual impairment faster than those without the condition.1,3

Glaucoma: This is a group of conditions that can damage the optic nerve. The optic nerve transmits signals from the retina to the brain for processing. Glaucoma is often (but not always) a result of increased pressure inside the eye. The risk of glaucoma in people with diabetes is significantly higher than that of the general population.1,4 The two main types are open-angle glaucoma (also called ‘the sneak thief of sight’) and angle-closure glaucoma (this comes on suddenly and is a medical emergency).

Design Methodology
performed an informational collection assortment, information resizing, information planning, and information expansion before using this model's preparation method after testing and approving the information. In this study, we combined the image processing capability with our own designed CNN architecture.

1) BACKGROUND OF CNN
An advanced neural network is one that uses convolutional networks. Deep learning was employed in the calculation. In order for the machine to decide which class to divide into, the computation is carried out by having the model first take an input image and then assign significance to various arguments or points of view in that image. The primary requirement for this model is prepossessing. The design of CNN features network diagrams of the neurons found in the human brain. Furthermore, 2D information picture structures have particular desirable positions. Slope-based augmentation is applied here. This model has a number of layers, such as convolutional and subsampling layers.

2) DATASET COLLECTION
Four different eye conditions will be covered in this paper: normal, diabetic retinopathy, glaucoma, and cataract.

3) DATA AUGMENTATION
We widened our informational collection to avoid overfitting. We added to our actual informational collection using five methods in order to broaden our important dataset and inspire us to group our model. A. Make a 90- degree turn B. Make a 90-degree turn C. Shading. D. A salt and pepper grind E. Horizontal Flip.

4) DATA PREPARATION
When we first started gathering the pictures, they were all in different sizes. Our informational index ranges in height, width, and size. In any case, our profound neural classifier needs a corresponding informational index in order to build and test the informational index. Therefore, the pixels were set to 224*224. Our model has nine layers. There are also three convolutional layers: ● The first layer has 16-3 3 filters and an activation function of "linear." ● The second layer has 32-3 3 filters, and the activation function is "linear”. ● The third layer has 64-3 3 filters, and the activation function is "linear”.

5) OCULAR DISEASE PREDICTION
We have used simple CNN and pre-trained models such DenseNet201 and EfficientNetB3 are used for correction.Comparative analysis is performed among models and the model that gives the highest accuracy is used for eye disease prediction.

Conclusion
We have gone through many steps in the advancements of medicine. In the near future, technology will be fast approaching and streamlining processes that usually took days, sometimes weeks to complete. The advantages of deep learning and artificial intelligence in diagnosis have been pointed out very heavily, and the most important part of the prediction taking very less time compared to an actual diagnosis, is reason enough to consider the use of Deep Learning for Ocular Diagnosis. The most immediate advantage of a faster diagnosis is the early detection of risk in patients with multiple ocular factors. There are many other advantages in the study of demographics and the deeper research of Ophthalmology. But still, after all these steps it is very important to consider some main steps: Firstly, even though the accuracy level of CNN is very high, it still has a slim probability of detecting the wrong disease. Secondly, the field of using deep learning and machine learning in medicine is fairly new. Newer algorithms need to be created and investigated for the field of medicine specifically so that the predicted output comes out even more accurately. Lastly, There needs to be easier ways to diagnose ocular disease. With these steps taken care of, ML will be able to swiftly streamline the diagnosis process.
