<h1 align="center" style="border-bottom: none">
    <b>
        <a> 🧠Brain Tumour Detection using CNN🧠 </a><br>
    </b>
     
</h1>

#   [`Demo video link `]([http://www.google.com](https://drive.google.com/file/d/1SdUxfdv9FH0OkDLlShCbkCK8hfnYspAd/view?usp=sharing) 
Brain tumor detection is the process of identifying the presence and location of a tumor in the brain. Early detection of brain tumors is crucial for improving patient outcomes, as treatment is most effective when the tumor is small and has not spread.
## Team Details
`Team number` : VH175

| Name    | Email           |
|---------|-----------------|
| DUDE NAGA SATYA SAI SIVA SANKAR | nagasivasankardude@gmail.com |
| PADALA DURGA PRASADU | 9921004520@klu.ac.in |
| RAYUDU CHARAN RANGA | charanranga2004@gmail.com |
| MAMIDALA PAVAN KUMAR | pavankumarmamidala23@gmail.com |


</div>

## Problem statement 
To Develop the various custom CNN models for Brain Tumour Detection and to identify the good accurate and efficient model to detect the brain tumour.
## About the project
- Convolutional Layer:
	This layer is the first layer that is used to extract the various features from the input images. In this layer, the mathematical operation of convolution is performed between the input image and a filter of a particular size MxM. 
- Pooling Layer:
	In most cases, a Convolutional Layer is followed by a Pooling Layer. The primary aim of this layer is to decrease the size of the convolved feature map to reduce the computational costs. This is performed by decreasing the connections between layers and independently operates on each feature map.
- Fully Connected Layer:
	The Fully Connected (FC) layer consists of the weights and biases along with the neurons and is used to connect the neurons between two different layers. These layers are usually placed before the output layer and form the last few layers of a CNN Architecture.
- Dropout:
	Usually, when all the features are connected to the FC layer, it can cause overfitting in the training dataset. Overfitting occurs when a particular model works so well on the training data causing a negative impact in the model’s performance when used on a new data.

 

## Technical implemntaion 
- Medical Imaging: Various imaging techniques are used to capture detailed images of the brain, including:
- Magnetic Resonance Imaging (MRI): MRI uses powerful magnets and radio waves to produce detailed images of the brain's structures, allowing for the detection of abnormalities such as tumors.
- Computed Tomography (CT)
- Preprocessing
- Feature Extraction
- Classification
- Validation and Testing
- Integration into Clinical Workflow
- Clinical Evaluation

## Techstacks used 
`CNN`, `ml`  

## How to run locally 
 
- Step 1 : using pip install the required packages
           Running a brain tumor detection system locally using Convolutional Neural Networks (CNNs) involves several steps.
- Step 2 : Data Collection and Preprocessing:
	Obtain a dataset of brain MRI images with corresponding labels indicating the presence or absence of tumors.
	Preprocess the images, which may involve resizing, normalization, and augmentation to improve model performance.
- Step 3 : Model Architecture Selection:
	Choose a suitable CNN architecture for the task. Common choices include architectures like VGG, ResNet, or custom architectures designed specifically for medical image analysis.
- Step 4 : Model Training:
	 Split the dataset into training, validation, and testing sets.
	Train the CNN model using the training set. During training, the model learns to differentiate between images with and without tumors by adjusting its parameters to minimize a defined loss function.
  	 Validate the model's performance using the validation set to tune hyperparameters and prevent overfitting.
	Evaluate the model's performance using the testing set to obtain final metrics like accuracy, precision, recall, and F1 score.
- Step 5 : Model Deployment:
	Once the model is trained and evaluated satisfactorily, it can be deployed locally for inference.
	You can integrate the trained model into an application or script that accepts MRI images as input and outputs predictions about the presence or absence of tumors.
	Use the deployed model to perform inference on new brain MRI images.
	Preprocess the input images similarly to the preprocessing done during training.
	Feed the preprocessed images into the trained model to obtain predictions.
	Post-process the model outputs as necessary (e.g., thresholding probabilities to make binary predictions).
- Step 6 : Evaluation and Iteration:
	Continuously monitor the model's performance on new data and iterate on the model architecture or training process if necessary to improve performance.
- Step 7 : Security and Privacy Considerations:
	Ensure that sensitive medical data is handled securely and in compliance with relevant regulations (e.g., HIPAA).
	Implement appropriate measures to protect the model and data from unauthorized access or misuse.


# What's next ?
The future of brain tumor detection is bright and focusing on improvements in several key areas:
- Advanced Machine Learning and AI: Deep learning algorithms are already showing promise in analyzing MRI scans for tumor detection with higher accuracy and earlier stage identification compared to traditional methods. This trend is expected to continue, with researchers creating more sophisticated models to differentiate tumor types and predict their behavior.
- Non-invasive techniques: Current detection methods like biopsies are invasive and can be risky. The future looks towards more widely available non-invasive techniques, potentially using blood tests or advanced MRI analysis to detect tumors.
- Multimodal Imaging: Combining data from different imaging modalities like MRI, PET scans, and CT scans is being explored to create a more comprehensive picture of the tumor. This can lead to more precise diagnoses and personalized treatment plans.
- Liquid Biopsy: Detecting tumor signatures in blood through liquid biopsies is a promising new approach. This could become a routine screening tool for early detection or to monitor treatment response.
- Focus on Personalized Medicine: By understanding the genetic makeup of individual tumors, treatments can be tailored to target specific mutations, leading to more effective therapies with reduced side effects.

