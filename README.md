# Election Hoax News Classifier
Classification of election-related hoax news using Bidirectional Long Short Term Memory (BiLSTM) and FastText Embedding, with unbalanced class handling using Borderline-SMOTE. 

*This research was conducted as part of the completion of the bachelor's program in Statistics, the Faculty of Mathematics and Natural Sciences at Padjadjaran University*

## Data:
Data in the form of Indonesian language news content with keywords related to the 2024 Election. Obtained from several online news sites, including:
1. cekfakta.com
2. turnbackhoax.com
3. kompas.com,
4. cnnindonesia.com

**Time period:** August to October 2023\
**Data retrieval:** Scraping process using Python and web scraper application, Octoparse.

## Steps:
![alt text](https://github.com/aissaputrip/Election_Hoax_News_Classifier/blob/main/images/alur_penelitian.png?raw=true)

## Conclusion:
This research aims to overcome these challenges by automatically classifying election-related hoax news on online media. Using the Bidirectional Long Short-Term Memory (BiLSTM) deep learning approach and fastText embedding, this research processed 6,076 Indonesian text data from online news sites from August to October 2023. The optimal model was formed with 1 fastText embedding layer, 1 BiLSTM layer (128 neurons), 1 dropout layer (40%), binary cross entropy as a loss function, Adam optimiser (learning rate 0.0001), batch size 16, and maximum epoch 100. Overall, the model successfully classified hoax news with a precision value of 85%, a recall value of 80.95%, and an F1-Score value of 82.93%, indicating the model is good enough to automatically detect hoax news.

## Additional code: 
Preview of Testing Prediction\
https://colab.research.google.com/drive/1hVm0rXsm065AQ2fmKLifMpnhSWUY5SGv?usp=sharing
