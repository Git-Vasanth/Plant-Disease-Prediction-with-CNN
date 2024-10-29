# Plant Disease Prediction with CNN

This project focuses on building an image classifier using Convolutional Neural Networks (CNN) for predicting plant diseases.

## Dataset Source
The dataset used for this project is the **Plant Village Dataset**, which contains images of healthy and diseased plants across 38 different classes. You can find the dataset [here](https://github.com/spMohanty/PlantVillage-Dataset).

## Project Outline

1. **Data Extraction**: Extract images from the Plant Village dataset organized by plant species and disease.
   
2. **Data Preprocessing**: Resize images to 224x224 pixels and apply data augmentation techniques.
   
3. **Data Preparation for Model Building**: Split the dataset into training (80%) and validation (20%) sets using image data generators.
   
4. **Model Building with CNN**: Construct a CNN model with convolutional and dense layers for classification.
   
5. **Model Training**: Train the model for 5 epochs, achieving a validation accuracy of **88.11%**.
   
6. **Model Evaluation**: Evaluate model performance with accuracy and loss metrics.
   
7. **Building a Predictive System**: Develop a function to preprocess images and predict plant disease classes.
   
8. **Deployment Using Streamlit App**: Deploy the model through a Streamlit application for user interaction.

## Performance Metrics
- **Validation Accuracy**: **88.11%**
- **Validation Loss**: **0.5387**

## Conclusion
The CNN model effectively predicts plant diseases, providing an accuracy of **88.11%**. The Streamlit application facilitates easy interaction, enabling users to quickly assess plant health.

## Future Work
- Explore transfer learning for improved model accuracy.
- Expand the dataset to include more plant species and diseases.
- Implement real-time prediction capabilities for practical field use.

## Full Report

For a comprehensive overview of the methodology, findings, and detailed analysis, please refer to the full project report linked below:

[I want to See the Report](https://drive.google.com/file/d/1euTxHE-1SHAQJI0L6z4TPsbhdHXtUEyn/view?usp=drive_link) 

[Download Full Report](https://github.com/user-attachments/files/17550470/Vasanth_plant.pdf)

![Test image 1](https://github.com/user-attachments/assets/a8fdf76f-fe90-4dcc-b35a-52245166da44)

![Test image 2](https://github.com/user-attachments/assets/d7613f5e-3f70-4be5-9a4a-d9ca530cbc0f)

![Test image 3](https://github.com/user-attachments/assets/30ac699b-d116-454c-9748-433463ccc1d2)


