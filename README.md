# CS6440
# Mental Health AI-Driven System Project

## Project Overview
This project aims to develop an AI-driven system that provides personalized mental health treatment recommendations based on user input. Users will complete a self-assessment, and the backend will analyze the data using two datasets—mental symptoms and drug treatments—to generate tailored treatment suggestions. The final product will be a single-page web application, with a backend powered by Python and AI models trained with Random Forest and SVM.

## Project Scope
1. **User Input & Assessment**: Users enter their information and take a self-assessment.
2. **Data Processing**: Self-assessment data is processed by the backend.
3. **AI Model Training**: Two datasets (mental symptom and drug treatment) train the AI model.
4. **Treatment Recommendation**: Based on the analysis, the system generates treatment suggestions.
5. **Results Display**: The personalized treatment plan is displayed on a dedicated page.

## Project Tasks and Timeline

| **Week**                                   | **Task Number** | **Task Description**                                                                                                                  | **Primary Contributor** | **Accomplishment** |
|--------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------|--------------------------|---------------------|
| **Week 1 - Data Preparation**              | Task 1          | Collect and verify the “Mental Health Synthetic” dataset from Kaggle.                                                                  | Yoon Kim & Patel Vraj    | O                   |
|                                            | Task 2          | Clean and preprocess the data, including handling missing values, normalizing data, and categorizing symptoms.                          | Yoon Kim                 | O                   |
|                                            | Task 3          | Conduct exploratory data analysis (EDA) to identify key patterns and distributions in the data.                                        | Yoon Kim                 | O                   |
| **Week 2 - AI Model Development**          | Task 1          | Define model objectives for both classification (mental health diagnosis) and regression (treatment recommendations).                  | Yoon Kim                 | O                   |
|                                            | Task 2          | Design and develop the UI using React.js, focusing on user-friendly input forms and a single-page layout.                              | Patel Vraj               | O                   |
|                                            | Task 3          | Implement and train initial models using Random Forest and SVM.                                                                        | Yoon Kim                 | O                   |
|                                            | Task 4          | Evaluate model performance with cross-validation and fine-tune hyperparameters to avoid overfitting.                                   | Yoon Kim                 | O                   |
| **Week 3 - Backend Integration**           | Task 1          | Set up the backend in Python, integrating it with the AI models.                                                                       | Yoon Kim                 |                    |
|                                            | Task 2          | Ensure secure data handling between the front-end and back-end, implementing API calls for data submission and results retrieval.      | Yoon Kim & Patel Vraj    |                    |
| **Week 4 - Testing and Evaluation**        | Task 1          | Conduct unit and integration testing on the AI models and the overall application.                                                     | Yoon Kim                 |                    |
|                                            | Task 2          | Perform user testing to gather feedback on UI/UX and model accuracy.                                                                   | Yoon Kim & Patel Vraj    |                    |
|                                            | Task 3          | Finalize any adjustments based on testing results and optimize performance for deployment.                                             | Yoon Kim & Patel Vraj    |                    |

                                      |

## Technology Stack
- **Frontend**: React.js
- **Backend**: Python
- **AI Models**: Random Forest, SVM
- **Data Sources**: Mental Health Synthetic dataset from Kaggle

## Risks and Considerations
- Dataset limitations may impact model accuracy.
- Possible overfitting; will require careful monitoring and adjustment.
- Additional treatment data may be needed to broaden recommendation capabilities.

## Getting Started
1. **Setup Frontend**: Install React.js and create the user interface.
2. **Setup Backend**: Configure Python environment and integrate AI models.
3. **Data Collection**: Gather necessary datasets and prepare them for processing.
4. **Run Application**: Start the server, run the frontend, and test the application.

---

### NLTK Coding Explanations
It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries, and an active discussion forum
