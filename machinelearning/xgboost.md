### boosting

    it is an ensemble technique which uses multiple decision tree,which is used for regression and classification
we use boosting when decision tree becomes underfit(it reduces the bias)
sequentially process all 100 trees

### xgboost:
    stands for extreme gradient boosting algorithm,which comes under boosting ensemble technique
*a technique uses internally

1]regularization--to find best wieghts(to reduces the varience)
2]gradient descent


### advantages of xgboost:
 1]scaling techniques not required
 2]handles missing values
3]handles categorical columns
4]works well with large datset
5] it handles both high varience and high bias


trees are dependent**********************

it reduces bias by reducing previous model mistakes


### decision tree models --weak learners

### how it works

  sigmoid for binary
  softmax for multi-class

##internally it uses regualarization thats why it reduces varience


bagging-- 
 100trees
 paralleling executes
 reduces varience
 random samples

boosting
100 trees
 sequentially executes
  reduces bias
  takes entire samples

best boosing algo-->xg boost
gives best accuracy comapred to random forest
why we use random forest?

small to medium size datsets,,but it becomes overfit
without using regu it reduces varience by

randomforestclassifier,xgboost --
diff-->
randomforestclassifier
bagging
executes parallel
trees independent
bootstarpng -->randomly
takes majority output ******
reduces varience
doesn't use regu
small datasets

xgboost
boosting
execeutes sequentially
trees are dependent
takes sigmoid output
reduces varience and bias
uses regualarizati
it handles categorical columns









