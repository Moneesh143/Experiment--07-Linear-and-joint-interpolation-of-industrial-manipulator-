# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 











 Robot movements:
 
 ![image](https://user-images.githubusercontent.com/97553333/206890082-0d427896-c9e6-487e-90cc-84fd2d1d6f62.png)
 
 ![image](https://user-images.githubusercontent.com/97553333/206890113-1f228835-cc3d-4eff-9ca9-ce8798cbf9bd.png)

![image](https://user-images.githubusercontent.com/97553333/206890118-39eb000b-8f08-4470-a0f5-0a0339c16a5f.png)

![image](https://user-images.githubusercontent.com/97553333/206890125-4f5295ef-ed46-437c-a619-ea01fa379e43.png)

![image](https://user-images.githubusercontent.com/97553333/206890155-fa7c4bfa-c220-4e72-aa71-52093e1ad960.png)

![image](https://user-images.githubusercontent.com/97553333/206890158-151630d9-18d1-44b4-936c-1200ef0e0b5b.png)

OUTPUT:

![image](https://user-images.githubusercontent.com/97553333/206890174-636db63b-3761-4274-87d9-631d7c4b2571.png)

![image](https://user-images.githubusercontent.com/97553333/206890176-a3383ca8-a1b7-45ed-8ad9-6b535c0081db.png)

RESULTS:

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



















### Results:  
