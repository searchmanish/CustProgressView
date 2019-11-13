# CustProgressView


To get a Git project into your build:

# Step 1. Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
	```
  
  ```

 # Step 2. Add the dependency
 
  dependencies {
	        implementation 'com.github.searchmanish:CustProgressView:1.0.0'
	}
	
	
  
  ```
 ```
 ## use in Xml file
  ```
  <com.sama.custprogress.SamaProgressView
        android:layout_width="32dp"
        android:layout_height="32dp"
        android:layout_centerInParent="true"
        app:dpv_inner_color="@color/colorPrimaryDark"
        app:dpv_inner_padding="8dp"
        app:dpv_outer_color="@color/colorAccent"
        app:dpv_thickness="2dp" />
	
