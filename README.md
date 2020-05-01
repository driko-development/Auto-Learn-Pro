# Auto-Learn Introduction
Auto-Learn is a machine learning Android application for our CSE3310: Fundamentals of Software Engineering class taken in Spring 2020. 

GitHub was used to host our git repository, it contains the following items:

* **AutoLearnApp** - Android studio project
* **Documentation** - Project Documentation
* **Machine Learning** - Dataset and ML material

# AutoLearnApp
### Prerequisites
* **Android Studio** must be installed ([Installation Instructions](https://developer.android.com/studio))

### Cloning the repository
From the cmd prompt or PowerShell type in the instruction 
**git clone https://github.com/willpanderson/Auto-Learn.git**
![](Documentation/Readme_Images/clone_repo.JPG)

Verify that you have the contents of the repository by listing the directory
![](Documentation/Readme_Images/list_repo.JPG)

### Launching the Android Application
1. Launch Android Studio <br /> <br />
![](Documentation/Readme_Images/open_android_studio.JPG)

2. Select **Open an Existing Android project** and navigate to the directory listed before 
![](Documentation/Readme_Images/find_android_project.JPG)

3. Click on the Android project denoted by the green **Android Logo** and hit **OK** <br /> <br />

4. Load an emulated device or connect a device (**Nexus 5x recommended**) <br />
  <details><summary><b>Instructions for Emulated Device</b></summary>
  
  1. From the Android Studio application, up at the top select **No Devices**
  ![](Documentation/Readme_Images/no_devices.JPG)
  
  2. Select **Open AVD Manager**
  ![](Documentation/Readme_Images/device_manager.JPG)
 
  3. From Device Manager select **Create Virtual Device**  <br /> <br />
  
  4. Select a device (**Nexus 5X** for testing purposes) and click **Next**
  ![](Documentation/Readme_Images/select_device.JPG)
  
  5. Choose Android version (**Nougat 7.0 minimum**) and click **Next**
  ![](Documentation/Readme_Images/android_version.JPG)
  
  6. Keep default settings and press **Finish**
  ![](Documentation/Readme_Images/default_settings.JPG)
  
  7. If the virtual device was created it will be displayed in the Device Manager
  ![](Documentation/Readme_Images/device_created.JPG)
    
</details> <br /> <br />

5. Select **Run 'app'** denoted by the Green arrow (Shift+F10) <br /> <br />
![](Documentation/Readme_Images/run_app.JPG)

6. For emulated devices the emulator will launch and the Auto-Learn application will be installed <br /> <br />

# Documentation
* **UML diagrams** - located inside of **Increment1_UML**
* **System Requirements Analysis** - located inside of **Increment2_SRA**
* **Test Plan** - located inside of **Increment3_TPL**
* **Final Documentation** - located in **Increment4_Final Binder**

# Machine Learning
### Data_Set
Our dataset consists of 5000+ images in a Google Shared Drive folder named [car_images](https://drive.google.com/open?id=1C1nC6vt0jxQ1o0sz7Ioq7MhCGv-PvNNT) which contains six folders representing our **six classifications**.
This is the dataset that was used to train the machine learning model generated by **FirebaseAutoML Vision Edge API**
* [AutoML Vision documentation](https://cloud.google.com/vision/automl/docs)

### TF_Model
Contains a google Collab with the code for our custom machine learning model. This model is currently being developed.


