# CSE523-Machine-Learning-2022-Hardly-Humans
## Project Title : Quora Insincere Questions Classifications
Quora is a website where a community of users can ask and answer questions. They may also create Q&A blogs and analyze statistics about the users as well. The relevance of question is often taken as into consideration and is necessary to prevent an unnecessary or redundant question that might affect different set of people. Quora Insincere questions arises when people ask questions that is intended to make statement rather than look for helpful answers. Questions consisting of an non-neutral term,  disparaging, inflammatory or is not grounded in reality can be classified as Insincere questions.

## Results:

1. LDA

![PR_ROC_LDA](https://user-images.githubusercontent.com/71372587/164989592-7cee3e11-5182-4582-a2fe-a529e177c6c4.png)

![confusion_matrix_LDA](https://user-images.githubusercontent.com/71372587/164989644-6518e611-80a1-4840-b66f-5ad25fc61dfa.png)

2. Logistic Regression

![PR_ROC_Logistic_Regression](https://user-images.githubusercontent.com/71372587/164989680-e5ede900-ae3c-49da-8e06-fa51305cc52b.png)

![confusion_matrix_Log_res](https://user-images.githubusercontent.com/71372587/164989686-8936676f-9ce4-4475-a01c-155fab8ce8ac.png)

3. SVM

![PR_ROC_SVM](https://user-images.githubusercontent.com/71372587/164989689-f1d7a059-3a66-4c54-8ed5-8f6676aabeae.png)

![confusion_matrix_SVM](https://user-images.githubusercontent.com/71372587/164989696-c7281bef-47d2-42fa-a2de-65d0c9890376.png)

4. Random Forest

![PR_ROC_Random_Forest](https://user-images.githubusercontent.com/71372587/164989712-f56c213d-83f4-4fcb-ad9a-d42083e5faf1.png)

![confusion_matrix_SVM](https://user-images.githubusercontent.com/71372587/164989721-257aca66-65df-4123-95f5-54069e15ac2a.png)

#References

1. S. T. Indra, L. Wikarsa and R. Turang, "Using logistic regression method to classify tweets into the selected topics," 2016 International Conference on Advanced Computer Science and Information Systems (ICACSIS), 2016, pp. 385-390, doi: 10.1109/ICACSIS.2016.7872727.
2. O. Aborisade and M. Anwar, "Classification for Authorship of Tweets by Comparing Logistic Regression and Naive Bayes Classifiers," 2018 IEEE International Conference on Information Reuse and Integration (IRI), 2018, pp. 269-276, doi: 10.1109/IRI.2018.00049.
3. “Sklearn.linear_model.logisticregression,” scikit. [Online]. Available: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html. [Accessed: 20-Mar-2022]. 
4. “Precision-recall,” scikit. [Online]. Available: https://scikit-learn.org/stable/auto_examples/model_selection/plot_precision_recall.html. [Accessed: 20-Mar-2022]. 
5. Y. Liu, J. Niu, Q. Zhao, J. Lv and S. Ma, "A Novel Text Classification Method for Emergency Event Detection on Social Media," 2018 IEEE SmartWorld, Ubiquitous Intelligence & Computing, Advanced & Trusted Computing, Scalable Computing & Communications, Cloud & Big Data Computing, Internet of People and Smart City Innovation (SmartWorld/SCALCOM/UIC/ATC/CBDCom/IOP/SCI), 2018, pp. 1106-1111, doi: 10.1109/SmartWorld.2018.00192.
