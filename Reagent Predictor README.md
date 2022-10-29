## Problem Statement:
The froth flotation technique is very essential to the economy of the world. Therefore, research is constantly needed to explore means of optimising it. A flotation process plan that lacks the appropriate dosage of reagents can lead to wastage of resources, compromised quality of the target material and financial loses. Hence, there is a need for means of predicting reagent dosages as accurately as possible.

## Research Questions:
• How does the numerical data gathered from previous iron ore flotation operations perform when used to predict the ideal amount of reagents needed for future ore processing? <br />
• Does a random forest regressor algorithm deliver accurate predictions for this project with an R2 score >0.95? <br />
• What effect would the development of the proposed application have on the metallurgy industry? <br />

## Aim and Objectives:
The aim of this project is to develop a software application that predicts the required dosage of depressant and collector reagents needed to process a given volume of iron and silica feed into a desired concentrate within a period of time. <br />
The objectives are:
• To research relevant previous work to determine the feasibility of the proposed solution <br />
• To obtain high quality data, pre-process it and achieve understanding of it <br />
• To research and conclude on the random forest regressor as a machine learning model that will accurately predict the target variables <br />
• To ensure the model performs as required by the pre-stated success and evaluation metrics <br />
• To develop a graphical user interface for the model. <br />

## Project Specifications: 
The proposed resource for this project is a software application made up of a predictive algorithm. It will be developed using the python language in the Jupyter notebook IDE. The application would require a large dataset made up of multiple variables associated with the froth flotation process such as date/time, percentage feeds, reagent flow, ore pulp flow, pulp, pH, density, flotation columns and the resulting concentrates. The application will be designed to take in a set of inputted variables needed for the prediction so that when prompted, it will deliver the corresponding predictions. To achieve a software artefact capable of predicting the dosage of reagents that would be needed to process a given volume of ore feed, the random forest regressor would be adopted. The data gathered specifically describes the flotation process of iron ore and silica ore simultaneously and previous work on this dataset was aimed at predicting the resultant percentage concentrate from the system. In this project however, the target variable would be the Starch and Amina flow (reagents) where the p-value technique of feature selection is implemented to realise the most important variables needed to achieve the proposed solution. Also, within this project, exploratory data analysis will be carried out on the data to achieve an understanding of how the variables relate to each other. Finally, the developed model will be linked to a graphical user interface window that prospective users can use to take advantage of the proposed solution within the industry. The project implements multiple python libraries among which are tkinter, numpy, pandas, sklearn, matplotlib, statsmodels and pickle.

The methods employed in the development of the project consisting of the data collection, pre-processing, EDA, modelling and GUI design

## Key Findings:
The exploratory data analyses revealed the behaviour of the key variables needed to predict the desired outcome. The uniform increment was illustrated and averaged out to show that the values of the variables tended to stay approximately similar throughout the recorded operation. This uniformity indicates that the output from the model can be used as a guide for operation planning and the benefits of the designed solution can be accrued. Although the correlation matrix technique yielded information that was adjudged to not be useful to the project, it was worth carrying out because the lack of correlation suggests that each variable functions independent of the rest when predicting reagent flow. The random forest regressor was also found to be an effective predictive model because it delivers an excellent R2 score and this fosters confidence in the results obtained from the execution of the model.

## Recommended Implementation of the Product:
The output of the prediction software is the starch and amina flow. Flow is the rate at which a fluid moves and is the product of multiplying the volume of the liquid by time. Hence, the output of the system can be utilised in two ways. The first one is that the derived suitable reagent flow informs the user of the rate at which the reagents need to be fed into the froth flotation system during the operation. Secondly, the predicted flow can be used to calculate the total volume of reagent needed for a set period of flotation operation which in turn inform the financial and operations plan for a proposed flotation operation.

## Benefits of the Software:
• The predicted values serve as a guide to the average flow of reagents that would be compatible with the inputted composition and density of the ore to be processed
• Project management related to a froth flotation operation can be assisted by the results obtained from utilising the product <br />
• Wastage of depressant and collector reagents will be reduced due to the optimised project planning afforded by the use of this solution <br />
• The quality of the processed ore will be enhanced through the accurate dosing of the reagents as concluded from past research. <br />
• Time taken to prepare for a flotation process is reduced since an easy method of reagent estimation has been introduced as opposed to the previously tedious methods. <br />
