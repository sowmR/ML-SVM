# ML-SVM

### SVM - Support vector machine 

**About**:
- Supervised label model
- It can be used by both Regression and Classification model
- It is good for Binary classification- For multi-class classification, there are certain tweek need to be made. Not used often in this use case
- Two main factors that defines SVM:
  - hyper plane - the line that separate two classes in a 2d image. When there is more dimension space, then it becomes a plane. 
  - Support Vectors - the points that are close to the hyperplane are called support vectors. If these points change, the hyperplane change accordingly.
   
![image](https://user-images.githubusercontent.com/26898960/145583730-c77faff6-b334-40c2-9068-315299504ae5.png)


**Pros**:

- This works well with small dataset

- It works efficiently when there is cleaner margin between two support vectors. If the margin between the two support vectors is large.

- It works well with high-dimensional data. (When there is lot of features in the data)

- It will be able to find the complex relation between the features. 

**Cons**:

- It is not suitable for the larger dataset since the training time will be higher

- Not suitable for noisier dataset with overlapping classes.

**Math behind SVM**:

When there is more dimension data , it will not be possible to draw a line. Hence it will become plane. 
the plane can be created by a mathematical function called "Kernel"

