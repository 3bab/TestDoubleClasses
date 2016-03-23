# TestDoubleClasses

While investigating JRE 1.8x class loading, I noticed that; if there are two classes with the same name, the Java class loader loads the one which is first in the class path.
The other class is ignored. 

## Testing ##

* Download the project
* Import the project into your Eclipse
* Run the app and check the output. You should see either "This is class A" or "This is class B".
* Change the order between A and B classes in the .classpath file
* Refresh and run the app again
* You should see that the output is different. That means that the class loader initialised another class

- - - -
![picture alt](http://luisjunqueiro.com/wp-content/uploads/2014/10/Untitled_Panorama1-Edit-3.jpg "Portugal")
