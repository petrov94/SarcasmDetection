# SarcasmDetection

This repository contains a natural learning processing project aimed at detecting various forms of figurative language such as sarcasm, irony, satire, understatement, overstatement, and rhetorical questions. The dataset is retrieved from SemEval-2022 Task 6: iSarcasmEval Task B called Intended Sarcasm Detection. The project utilizes BERT, BERTweet, and LSTM models to classify text data into these categories. The classes separation is as follows :

<img width="539" alt="image" src="https://github.com/petrov94/SarcasmDetection/assets/15279876/8d6681b1-8e1a-42c1-8e57-a2db7ae7a6f8">

Due to unbalanced data, these experiments used different loss functions like Cross-Entroy loss, Folcal loss, and LSTM experiments with weighted Cross-Entropy. 
Moreover, as an extra step was generating more examples using GPT 3.5 which fixed the class imbalance.  More information about the whole experiment can be found in the documentation.doc file.


