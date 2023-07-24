# Sentiment analysis on MDB movie review with naive bayes classifier

This project implements a naïve bayes classifier from scratch on MDB movie review datasets to predict weather a review is positive or negative.

The baseline model is a binary naïve bayes classifier built from scratch, with k = 1. The final accuracy of the baseline model is 0.825, and the F1 score is 0.830.

The study consisted of two experiments: 

(1) Exploring the effect of k-smoothing on the classifier's performance.

The results show that k-smoothing can significantly improve the classifier's performance but keep increasing k value can only yield a slightly better performance. In this case, the best F1 score is 0.838 when k = 20(the biggest k value in our experiment).




(2) Examining the impact of Byte Pair Encoding (BPE) on the classifier's performance.

BPE did not lead to improved performance in this study, it reduced the vocabulary size(from 30948 to 9918) but negatively impacted the classifier's accuracy. The final accuracy of the BPE-NB model is 0.623, and the F1 score is 0.708, which is not as good as the baseline model.


__more details and discussion can be find in `NB_report.pdf`__
