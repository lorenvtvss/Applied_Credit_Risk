# Applied Credit Risk Modelling 

#### Developing a Probability-of-Default (PD) Model via Neural Networks 

**Research Paper**: Angelini, E., Di Tollo, G., and A. Roli (2008). A Neural Network Approach for Credit Risk Evaluation, p. 733-755. The Quarterly Review of Economics and Finance.


Angelini et al. (2008) discuss in their paper “A Neural Network Approach for Credit Risk Evaluation” the application of neural networks to credit risk assessment. 

Following the Basel Committee on Banking Supervision (2005) framework for capital adequacy, banks are permitted to determine the capital requirement through internal evaluations of key risk factors. The resulting need for robust credit risk assessment systems prompted the exploration of whether more advanced models like an artificial neural network could yield promising outcomes in this field.
For this purpose, Angelini et al. (2008) developed two neural network systems: First, a standard feedforward network, composed of an input layer, two hidden layers and an output layer. Second, a feedforward network with ad hoc connections, composed of four layers, with the input neurons grouped by three. Both the networks have been trained utilizing the backpropagation algorithm, which optimizes the network weights by minimizing the error between the desired and the actual output, using a careful choice of parameters. The models are then trained and tested on real-world data, related to Italian small businesses. 

The results for both networks demonstrate the effectiveness of the approach, resulting in a system that is capable of accurately classifying inputs with a low error. Angelini et al. (2008) describe the performance as a “state-of-the-art result”. According to the authors, the careful analysis and normalization of the data is one reason for this performance, highlighting the importance of an elaborated data cleaning process. 

The application of neural networks in praxis is widely distributed and is classified in three main categories by the authors. Frist, classification and discrimination, used in credit risk assessment and bank failure prediction. Second, series prediction, used to forecast prices and performances of financial products, financial crashes, economic crisis warnings and predicting pupil expenditure in public school. Third, function approximation and optimization for portfolio selection and rebalancing, and investment project return prediction.

To be highlighted is the comprehensive analysis conducted by the authors on parameter tuning, a pivotal aspect in machine learning. Further, they tested the model robustness using various train test splits. Nonetheless, labeling their results as "state-of-the-art" may be overly optimistic, as they did not include the recall value, a crucial performance metric in credit risk assessment. Additionally, to ascertain the model's robustness, it would be advantageous to apply it to a different dataset. 

In contrast to Angelini et al. (2008), we analyzed important performance metrics, such as recall, and conclude that neural networks may not be the optimal approach for credit risk assessments. The discrepancy between our findings and those presented in the paper could potentially stem from variations in the setup, dataset, or network models. It needs to be pointed out, that the authors only reported the best performing network results, introducing a reporting bias.
$
In conclusion, neural networks possess the inherent capability to capture non-linear relationships, which distinguishes them from basic regression models. However, their practical application is constrained by their black box nature, resulting in limited interpretability and regulatory restrictions. We agree with Angelini et al. (2008) regarding the potential of neural networks in credit risk assessment, provided that attention is given to methodological and application issues.
