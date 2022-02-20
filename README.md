# Discourse Classification


### Description
Discourse_classification is a BERT model designed to identify different discourse elemenents in a student's writing. The model is fine-tuned for NER Token Classification and uses the Kaggle [Feedback Prize - Evaluating Student Writing](https://www.kaggle.com/c/feedback-prize-2021/data) dataset for training.

#### All Discourse Elements (NER Token Classifiers)
First, the model divides the corpus into distinct discourse elements and then the elements are classified as one of the following...
- Lead: an introduction that begins with a statistic, a quotation, a description, or some other device to grab the reader’s attention and point toward the thesis
- Position: an opinion or conclusion on the main question
- Claim: a claim that supports the position
- CounterClaim: a claim that refutes another claim or gives an opposing reason to the position
- Rebuttal: a claim that refutes a counterclaim
- Evidence: ideas or examples that support claims, counterclaims, or rebuttals
- Concluding Statment: a concluding statement that restates the claims

### Example
<img src="vidSLAM_example2.png" width="400" height="300">
