# FP-Fake-News-Detection
[CM3070] Final project module, Fake news detection template

The rapid spread of misinformation and the rise of AI-
generated content present new challenges in detecting
and mitigating fake news. This project aimed to de-
velop an effective, explainable, and scalable fake news
detection model capable of distinguishing between real,
fake, and AI-generated news. By leveraging state-of-
the-art transformer models, including DistilBERT, and
deploying a real-time Streamlit web app, this study pro-
vides a novel multi-class classification approach beyond
the traditional binary models used in fake news detec-
tion.

To build this system, WELFake [19] and GPT-2-output
[20] datasets were preprocessed through extensive data
cleaning, balancing, and exploratory data analysis
(EDA). Multiple methodologies were explored, starting
with traditional ML models such as Logistic Regres-
sion, SVM, and Random Forest, before transitioning
to FastText with BiLSTM and transformer-based mod-
els (RoBERTa, DistilBERT). The final model, Distil-
BERT, was chosen due to its exceptional accuracy, effi-
ciency, and scalability. Furthermore, extensive evalua-
tion, including performance metrics analysis, confusion
matrices, AUC-ROC, Precision-Recall analysis, strat-
ified k-fold cross-validation, and cross-dataset valida-
tion, demonstrated the model’s robust generalization
ability, achieving a cross-validation accuracy of 96.42%
and a cross-dataset validation accuracy of 96.53%.
