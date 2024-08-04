# Enhancing E-commerce Product Classification with BERT: Leveraging Amazon Dataset for Precise Categorization
## Description
This project focuses on improving product categorization in e-commerce using BERT, a sophisticated language model, fine-tuned on Amazon’s dataset. The goal is to address challenges such as complex product descriptions, inconsistent annotations, and inaccurate labels by employing advanced machine learning techniques to enhance categorization accuracy.

## Abstract
Product categorization is critical in e-commerce for enhancing operations, optimizing inventory management, and enabling data-driven decisions. However, challenges persist due to complex product descriptions, inconsistent annotations, and inaccurate labels. This project advances product categorization by employing BERT, a sophisticated language model, fine-tuned on Amazon’s dataset to tackle these issues as a multi-label classification challenge. By encoding product titles and descriptions into a comprehensive semantic framework and experimenting with various hyperparameter tuning strategies, we have tailored BERT to better capture the unique attributes and specialized knowledge inherent in e-commerce products, significantly improving categorization accuracy.

## DataSet

Download the dataset from the following link and place it in the project directory:
[(https://drive.google.com/file/d/1ILRl6FdugUuAA5Mmkt1bG5ExPYrggAoG/view?usp=drive_link)]

## Running the Code
To train the model, use the `main_train_model` script. 
Ensure the following files are in the same directory:
- `model_architecture`
- `main_train_model`
- `main_evaluate_model`

    To evaluate the experiments provided in the report, download the following files and place them in the project directory:

    - `model_project10k-gamm65-12Freeze.pth`
(https://drive.google.com/file/d/1hdlyyZ6gx58yO5X9aeCnTrnLZH7rUFaq/view?usp=drive_link)
    - `model_project10k-gamm65.pth`
(https://drive.google.com/file/d/1BzLU3A7usxTmo9N7DzrWbC40qkdbl-ad/view?usp=drive_link)
    - The dataset mentioned above

To evaluate the models provided in the project report, use the `main_evaluate_model` script. 
    If you want to evaluate the best model, you should put the ‘name’ variable in the code  = best . If you want to see the result of BERT with 12 layers frozen, put ‘name’ variable in the code  = to freezed.

## Technical Report
Project_Report.pdf
