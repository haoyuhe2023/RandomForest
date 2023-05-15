# RandomForest
Random Forest(python without liarbries)
following tasks are accomplished in this project:
✓ Decision tree (without stop-split-early condition)
It includes the following components:
1) Calculate information gain; 
2) split the data via finding the best feature based on 1); 
3) create branches recursively based on 2) until every leaf only contains a single category; 
✓ Random Forest
4) Bagging. Perform 100 Bootstrapping on the data, generate different decision trees based on task
3), and perform majority-voting on their prediction results. 
5) When each node of the decision tree is split, 3 features are randomly selected in the way of
non-replacement sampling, and task 2) is performed accordingly. 
