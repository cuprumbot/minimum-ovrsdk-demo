# minimum-ovrsdk-demo

### Problem to solve
The example found at https://github.com/wwwtyro/node-ovrsdk works in my terminal but fails when used inside a node-webkit app

The problem occurs in the instruction `libovr.ovrHmd_StartSensor(hmd, ovrSensorCap_Orientation, ovrSensorCap_Orientation);` and the error I am getting in the console is `Uncaught ReferenceError: ovrSensorCap_Orientation is not defined`

### Instructions
Inside the app directory install node-ovrsdk (`npm install node-ovrsdk`) and printf (`npm install printf`). Rebuild ffi and ref as instructed in http://www.tyrovr.com/2014/06/01/nw-ovrsdk-tutorial.html 

Connect an Oculus Rift an run the app using node-webkit 0.8.6