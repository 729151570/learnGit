## 训练参数
batch_size 32  
train_epochs 27  
Accuracy: 0.6820

Classification Report:

              precision    recall  f1-score   support

           0       0.67      0.65      0.66      1298
           1       0.62      0.70      0.66      1579
           2       0.57      0.41      0.48      1177
           3       0.47      0.45      0.46      1520
           4       0.88      0.96      0.92      2471

    accuracy                           0.68      8045
   macro avg       0.64      0.63      0.63      8045
weighted avg       0.67      0.68      0.67      8045

Confusion Matrix:

[[ 848  137   61  220   32]  
 [ 115 1100   55  222   87]  
 [ 148  117  483  289  140]  
 [ 153  388  215  685   79]  
 [   9   27   27   37 2371]]