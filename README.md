# common_utils
this project contains some common utilities that are required by Android DEVs

at present it have : 
1- Toaster feature
2- Check if internet connected feature
3- To show progress dialog  and dismiss progress dialog


How to use it?

Step 1. Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.snjiv:common_utils:1.0'
	}
  
  Then in your project
  
  just type " Utils." it will show all the methods. Please select any according to your requirement.
  
  
