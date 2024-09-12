# Module 21 Report 
1.  **Overview**  of the analysis: The purpose of this analysis was to determine which organizations had the best chance of success in their ventures    
2.  **Results**: 
-   Data Preprocessing
    
    -   The model targeted APPLICATION_TYPE  and CLASSIFICATION
    -   The features for the model included the variable **IS_SUCCESSFUL**
    -   The variables removed were EIN, STATUS and SPECIAL_CONSIDERATIONS. They were removed since there were only a small percentage of projects that were in the minority categories
  -	Compiling, Training, and Evaluating the Model
    
    -   3 hidden layers and an output layer with an activation function were used to adjust the input data to ensure no variables or outliers caused confusion to the model
    -   The model was able to reach an accuracy of around 79%, greater than the accuracy goal of 75%
    -   In order to increase the model performance, STATUS and SPECIAL_CONSIDERATIONS variables were removed from the original analysis

3.  **Summary**: Overall, the model was able to produce the desired effect for Alphabet Soup. It is recommended that Alphabet Soup use the optimized model when making their considerations of the applicants. With the outlying variables removed, it gives the organization a better view when determining the applicants for funding with the best chance of success in their ventures.
