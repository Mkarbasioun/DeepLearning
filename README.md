# DeepLearning


First Lesson in Deep Learning: Logistic Regression

Logistic Regression Using Sigmoid Function as Cost Function

Sigmoid Function in range of 0 to 1

#Algorithm:

1-Calculate Logistic Regression Z = b + w1 * x1 + w2 * x2 + .... 
2-Calculate Sigmoid function of Z as cost function (simoid(Z) = 1/(1+exp(-Z)))
3-We want to find w:
  3-1- Initialize w = 0
  3-2- Repeat w:= w-alpha*dw  (dw = dJ/dw)
4- We want to find b:
  4-1- Initialize b = 0
  4-2- Repeat b:= b-alpha*db (db = dJ/db)
