# Covid-19 Tracker
-----------------------------

## Setup

* Install Python 3.9.0
* Install Tensorflow 2.1 from **[here](https://www.tensorflow.org/install)**.
* Install MediaPipe  **[here](https://google.github.io/mediapipe/getting_started/python)**
* Install pip 21.0.0
* Install OpenCv 2.0 from pip
* Install Django from pip
* Install Numpy, Pandas, Matplot.lib from pip
* Install Utiles from pip
* Install other dependent module which is depend on above any.


## Development

* Set the appEnvironment property in the file src/environments/environment.ts to the required environment using the AppEnvironment enum (Development,
  Testing,
  Production,
  Developement).
  
*Note: For production build, environment.prod.ts is the environment file used.*



* Application Entry Point
Go to root directory
Open Developement Console or Powershell and type below command

```
 run python manage.py runserver
 type localhost:8000 on the browser
```

*Important thing use google chorme in developement mode or use another web broswer for smooth exectuion.

## Application Flow
* index.html -> entry web file
  **Tooggle camera -> On/off the camera
* warning.html -> redirected if detected drowsiness.
* suggestions.html ->  redirected if user interact with application and turn the alarm off.



## To Start the module to run AI model alone.
Go to main.py file and run it with python.
