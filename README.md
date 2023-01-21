# Kaggle Feedback-Prize---English-Language-Learning 37th place solution

This is repository of the 37th place solution of Kaggle [Feedback-Prize-English-Language-Learning](https://www.kaggle.com/competitions/feedback-prize-english-language-learning/overview).  
The discription of this solution is available [here](https://www.kaggle.com/competitions/feedback-prize-english-language-learning/discussion/371602).

# Hardware
I used Google Cloud Platform

- Environment: Kaggle Python  
- Machine Type: 4 vCPUs, 15 GB RAM  
- GPU: 1 NVIDIA T4  
- Boot Disk: 100 GB Standard persistent disk  
- Data Disk: 100 GB Standard persistent disk  

# Data download
Plese download data to ./feedback-prize-english-language-learning from https://www.kaggle.com/competitions/feedback-prize-english-language-learning/data and unzip it.

# Model download
I used several pretrained models that are publicly available in the kaggle dataset. Please download it to the ./models and unzip it.

# Train
You can train various models such as DeBERTa, RoBERTa, Funnel, etc. through the notebook located at "./exp."  
In our team's final submission, we also utilized [publicly available models](https://www.kaggle.com/code/kojimar/fb3-deberta-family-inference-9-28-updated).

![スクリーンショット (303)](https://user-images.githubusercontent.com/82075657/213848684-6b359fb0-f3eb-48bf-8587-20d22f5fcec0.png)
