## naive bayes
naive-- it assumes all features are independent
bias- classifies labels using bias theorem using highest probability

### what is nb?
it is supervised learning algorithm which is used for classification scenario and it uses probability to predict the class labels based on highest possibility


### where we use this?
sentiment analysis
medical diagnosis


### why it is used?
when it is comapred to sentence based classification it performs better than the all the algorithms except logistic regresssion


### 3 algorithms
1. bernoulli naive bayes-->when all feature columns are binary
2. gaussian naive bias--> this we use when feature columns are continuous values(ex:medical dataset)(not target)
3. multinomial naive bais -->this is used when we are making sentence based classification

### SENTENCE BASED CLASSIFICATION
 1. logistic 
 2.multinomial naive bias
  why we use them?
  both uses probability 


# fastest algorithm among all supervised learning algorithms 
why?
here also it stores the data along with it ,it uses probability
during model prediction :actual calculation will be done


### code:
 
from sklearn.naiv_bayes import BernoulliNB,GaussianNB,MultinomialNB

