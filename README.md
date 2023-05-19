### Graduate Big Data:
# Emotion Sentiment Classification of Product Reviews on Twitter

## Motivation
It is considerably more difficult to discern someone's tone in writing than it is in conversation. For starters, you cannot infer an author's emotional condition from their facial expressions or body language. For instance, the tone of a message is typically not determined by a single characteristic. Numerous aspects are involved in effective communication. Because in some circumstances, what you say can be just as important as how you say it. Our approach is designed to offer feedback on a variety of keywords that represent the emotion of the message. It's also helpful in ensuring that your recipient will focus on the facts you are presenting rather than unintended consequences of your tone by making strategic judgments about how you convey your message.

## Proposal

To Implement two pipeline in AWS to categorise the Article/Conversation into 6 Classes (happy, angry, surprise, sad, disgust, not-relevant).

1. **Pipeline-1 : Using Spark-MLlib to implement Logistic Regression, Random Forest and SVM**

![SparkMl](https://github.com/Ashleshk/Emotion-Sentiment-Classification-of-Product-Reviews-on-Twitter/blob/main/BERT%20Results/arch1.png)

2.  **Pipeline-2 : Using Sagemaker to implement Deep Learning Model including BERT, Roberta, and RNN.**


![ML in Sagemaneker](https://github.com/Ashleshk/Emotion-Sentiment-Classification-of-Product-Reviews-on-Twitter/blob/main/BERT%20Results/Arch-02.png)

## Result

Achieved 97.83% accuracy and 0.83 F1-score on RNN model.

