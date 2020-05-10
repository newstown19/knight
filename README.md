# knight
project for knight FinTech
The approach is something like this , I've used a language model and a multiLayer Perception model for text features and categorical features respectively.
features include 'review_description' for language model , 'province' and 'winery' for MLP. The Model is trained on 3 inputs.

MODEL : The Language model is trained with an Embedding layer , to reduce overfitting and fast computation dropout and BatchNormaliztion are used respectively.
        Output is predicted as softmax activation.
        
        ACCURACY achieved 88% on trainingData
        
VISUALIZATION: visualization and insights about data is provided in Visualisation.ipynb 

final ouput is stored in prediction.csv
