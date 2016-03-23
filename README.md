# TestDoubleClasses

While investigating JRE 1.8x class loading, I noticed that; if there are two classes with the same name, the Java class loader loads the one which is first in the class path.
The other class is ignored. 

## Testing ##

* download the project
* import into your Eclipse
* run the app and check output
* change the order between A and B classes in the .classpath file
* refresh and run the app again
* you should see that the other class was initialised

- - - -
![picture alt](http://luisjunqueiro.com/wp-content/uploads/2014/10/Untitled_Panorama1-Edit-3.jpg "Portugal")
