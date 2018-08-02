# lesson18
Inheritance and Polymorphism
We are going to skip task 6 where the programmer makes the menu for his simulator.  You can access a complete version of the app up through task 6 on github.  Continue using the link below.  You are responsible for task 7.  Upload your completed potato class. Then you will be making your own wheat class.

### Enhancement -  Making the Wheat Class

1. Let's assume that wheat is a crop that really likes sun yet doesn't like too much water.  Set the growth_rate to 1, the light_need to 5 and water_need to 2.

2. If wheat gets more than 8 light while it is in the "young" stage, then it will grow twice as fast.

3. However, when it is in the "seeding" stage and water is above 7, then it will only grow half the speed.

4. When it is in the "mature" stage, it doesn't grow at all.

5. The wheat class should inherit from the crop super class and you should override the grow function similar to what was done in the video.

6. Save it as wheat_class.py and upload it to the lesson 18 repository.

7. Use crops.py to test both your potato and wheat crops.

Discussion Questions

1) Describe how programmers save time using inheritance.

2) Describe Polymorphism.

3) What is the advantage to having the growth function share the same name with the parent growth function.  Why not call it potato_growth?
