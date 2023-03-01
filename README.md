
Luis F Lopez Penunuri
February 28, 2023
IT FDN 110 A
Assignment 07
https://github.com/fernandoPenunuri34/IntroToProg-Python-Mod07.git
	
	# Assignment 07

## Introduction
This assignment required us to implement exception management. Root gave us the opportunity to choose what we wanted to do to implement it. In my practice, I continued talking with Jose to understand his needs. He said that he was having issues with his clients since most of them use imperial system metrics (lbs and inches), but he only understand international metrics (mts and kg). So, I wanted to help him by creating a script that would assist him in making the conversions.

## Practice
In this practice, we implemented 'Try-Catch' to handle exceptions. To understand it better, I implemented as many as I could. The try-catch block allows us to catch and handle exceptions so that the program can continue executing instead of crashing. The try block contains the code that may raise an exception, while the except block contains the code that should be executed when an exception occurs (Figure 7.1).



![image](https://user-images.githubusercontent.com/1307961/222068755-9796f316-943a-460b-8e66-5ec62eff02fd.png)







*Figure 7.1 Handle Exception*




![image](https://user-images.githubusercontent.com/1307961/222068785-3cd8a1b0-f5cd-427f-9f64-54843841a351.png)








*Figure 7.2 Handle Exception in the Main*


 
## Using Method:
### Dictionary: 
The menu is being handle by a dictionary called ‘operations’ that maps strings representing different types of conversions to the corresponding conversion functions defined in ‘calculator’ module. 

The key is a string that represents the user’s choice of operation, while the value is the corresponding function that will be executed when the user selects that option (Figure 7.3).



![image](https://user-images.githubusercontent.com/1307961/222068861-ea4ef812-32a1-43d6-a3d4-2d6e013031cc.png)

*Figure 7.3, Dictionary to handle the menu*


### self.num1
‘Self’ refers to the instance of the class that the method belongs to. In script, ‘self.num1’ refers to the ‘num1’ attribute of the instance of the ‘Calculator’ class. 

In the same section of the contractor, the ‘_ _init_ _’ method is a special method in Python classes that is called when an instance of the class is created. The self.num1 = num1 statement in the __init__ method initializes the num1 attribute of the instance with the value passed to the method as num1.
The other methods in the Calculator class also use self.num1 to perform calculations based on the value of num1 stored in the instance.






![image](https://user-images.githubusercontent.com/1307961/222068885-8471415f-17e9-42b8-83bc-1ba519961996.png)
















*Figure 7.4 Init method (https://www.w3schools.com/python/gloss_python_class_init.asp)pickle*

The pickle module implements binary protocols for serializing and de-serializing a Python object structure *(taken from https://docs.python.org/3/library/pickle.html)*.

In this code, I'm using the dump function to serialize an object hierarchy. This function writes the pickle representation of the object obj to the open file object file.
Pickle.loads returns the reconstituted object hierarchy of the pickled representation data of an object. The data must be a bytes-like object. The protocol version of the pickle is detected automatically, so no protocol argument is needed (taken from https://docs.python.org/3/library/pickle.html) (Figure 7.5).







![image](https://user-images.githubusercontent.com/1307961/222068927-779f4cce-a79b-4a09-b400-415498c2f0a9.png)









*Figure 7.5 pickle example*







## Prove 
Option number 1 will do a conversion to feet from meters (Figure 7.6).






![image](https://user-images.githubusercontent.com/1307961/222068976-17725c69-a395-4e15-9a4e-ae205da362c9.png)










*Figure 7.6 Option 1*

Option number 2 will do a conversion to meters from feet (Figure 7.7)
















*Figure 7.7 Option 2*


Option number 3 will do a conversion to lbs from Kg (Figure 7.8).






![image](https://user-images.githubusercontent.com/1307961/222069050-69a77ca0-8f0f-425b-b454-c05cc1775a8b.png)










*Figure 7.8 Option 3*

Option number 4 will do a conversion to Kg from lbs (Figure 7.9)








![image](https://user-images.githubusercontent.com/1307961/222069092-b296b8ce-9337-4a36-80f5-b8d2fec19708.png)








*Figure 7.9 Option 4*



## Conclusion
This was a very interesting practice. I wasn't that creative, but it was nice to search for this information and understand it. On the other hand, handling exceptions was a good way to prevent errors in the system. I really like how it works and how easy it was to implement.

Jose was amazed by the program and how easy it was use. Now he has a tool to continue with his work. However, he was not sure if it is good enough, so I made a deal with him.




Whether or not I can make a good amount of guacamole for the carne asada is up to you. 
