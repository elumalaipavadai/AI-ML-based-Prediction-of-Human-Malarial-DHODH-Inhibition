# AI/ML-based Prediction of Human Malarial DHODH-Inhibition
Quantitative Structure-Activity Relationship (QSAR) model using AI/ML for the prediction of the inhibition activity of Human-Malarial-DHODH

## Project Description

This project aims to address the urgent need for novel antimalarial treatments by leveraging AI/ML approaches. By integrating datasets of chemical compounds of validated drug target and their drug response profiles, this project fills critical gaps in traditional drug discovery pipelines, accelerating the identification and optimization of promising lead inhibitors for Human Malaria Parasite Plasmodium Falciparum Dihydroorotate Dehydrogenase (DHODH). The main goals include predicting the DHODH inhibition activity of candidate compounds, elucidating their structure-activity relationships, and prioritizing compounds for further experimental validation. Through this innovative approach, the project aims to expedite the discovery of effective antimalarial drugs, ultimately contributing to the global effort to combat malaria.
The solution workflow begins with DHODH data collation and preprocessing and feature engineering, followed by model training and validation. 

## Solution Description

![Workflow](https://github.com/elumalaipavadai/AI-ML-based-Prediction-of-Human-Malarial-DHODH-Inhibition/blob/main/Malaria_workflow.png)

The solution involves several key steps as explained in the workflow above:

1. **Data Collection and Preprocessing**: Obtain data from the ChEMBL for malaria drug target Dihydroorotate Dehydrogenase (CHEMBL3486) and preprocess it using Pandas and Numpy.
2. **Feature Engineering**: Extract relevant chemical features from molecular structures using PaDEL and PubChem software.
3. **Model Training and Evaluation**: Train and evaluate various ML algorithms, such as random forest, support vector machines, or neural networks, using the preprocessed data to predict the activity of potential drug candidates against malarial Dihydroorotate Dehydrogenase target.
4. **Future Enhancements**: In the future state, the solution aims to streamline the model pipeline further by implementing advanced techniques for feature engineering, such as deep learning-based representations. Additionally, integration with Streamlit web app and high-throughput screening assays can enhance scalability and efficiency.

## Solution Design

### Solution Code Description:

The solution code for building a machine learning model for malarial DHODH target is implemented in Python and utilizes several key software packages:

- **Data Preprocessing**: Pandas, scikit-learn, rdkit
- **Machine Learning Algorithms**: scikit-learn.
- **Model Evaluation and Metrics**: scikit-learn.
- **Visualization**: Matplotlib, seaborn.
- **Optional (for deep learning)**: TensorFlow, PyTorch.

The code is organized into modular functions and classes to facilitate readability, maintainability, and reusability. Comments are included throughout the code to explain the purpose of each section and provide guidance for users.

### Actual Working Product Code:

The code includes functions, modules, packages, and documentation for easy usability.

## Application Instructions

### Step-by-step instructions for Usage:

1. **Installation**:
   - Clone the repository: `git clone https://github.com/yourusername/malarial-dhodh-prediction.git`
   - Install dependencies: `pip install -r requirements.txt`
   
2. **Usage**:
   - Follow instructions in the README.md for data preprocessing, model training, and evaluation.
   
3. **Additional Guidelines**:
   - Ensure proper configuration and folder structure as specified in the README.md.
   - Use provided batch scripts for environment setup and package installation.

## Contributing

Contributions are welcome! Please refer to the CONTRIBUTING.md file for guidelines.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

