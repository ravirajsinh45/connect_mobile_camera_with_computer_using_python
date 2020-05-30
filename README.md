# connect_mobile_camera_with_computer_using_python
Code regarding connect any android or Iphone mobile camera with computer for python and openCV.

Some time you have to do live streaming or have to run object detection model with camera and you don't have high quality camera, well solution is here.

# Setting up the repo:-
Clone repo to your computer
```
git clone https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python.git
```

change directory 
```
cd connect_mobile_camera_with_computer_using_python
```

Now install require libraries.
```
pip install -r requirements.txt
```

Their are two way to connect camera with pc
1. Using USB cable
2. Using WIFI


# Steps Using USB:-

## For IOS device


1. Download Droidcam app on your IOS device from [app store](https://apps.apple.com/us/app/droidcam-wireless-webcam/id1510258102)
![](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/images/app_store.jpeg)

2. Download and install [Dev47app](https://www.dev47apps.com/droidcam/windows/) setup on your pc for ios devices.

3. Plug the device with PC and open Droidcam on your iphone you will get screen like this ![](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/images/app_screen.jpeg)

4. open Droidcam app on pc and click on USB button, you will get screen like this ![](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/images/pc_screen_of_droidcam_client.jpg)

5. Hit first refresh button and will get your device id in box than after hit start button and you will get camera input on your computer screen.

6. From using_USB folder open [camera_input_for_IOS_device](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/using_USB/camera_input_from_IOS_devices.ipynb) and run the code.

## For Android device
here is documantation by [Droidcam](https://www.dev47apps.com/droidcam/connect/)


1. Download droidcam app on your Android device from [play store](https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&hl=en_IN)
![](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/images/play_store.jpeg)

2. Download and install [Dev47app](https://www.dev47apps.com/droidcam/windows/) setup on your pc.

3. On the phone, go to Settings -> Developer Options, and enable “USB Debugging”. 
    - (In case) On most phones the Developer options screen is hidden by default. To make it visible, go to Settings > About phone and tap “Build number” 7 times. Return to the    previous screen to find “Developer options” at the bottom.

4. Plug the device into computer over USB and open Droidcam app. 
    - If you get a dialog on the phone asking “Allow USB Debugging”, you need to tap OK. 
    - If you get dialog `Use USB for` When you plugged in, give permission for Photo transfer(PTP)
    ![](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/images/android_screen.jpeg)

5. open Droidcam app on pc and click on USB logo and press refreash button, you will get your device name or some random string(unique id). 

6. Add port which is showing in your mobile screen(generally 4747). 

7. Hit start button and you will get camera input on your computer screen.

8. Open [this notebook](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/using_USB/camera_input_from_Android.ipynb) run the code and you will get your mobile camera input(make sure you installed all libraries using requirements.txt).


# Steps Using Wifi

## For Android devices
### Using IP Webcam app
1. Download IP Webcam application from [play store](https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en_IN)

2. connect both mobile and computer with same **Internet**
    - If you have wifi than connect both computer and mobile with wifi
    - If you do not have wifi than turn on mobile hotspot and connect PC with it.

3. Open Ip Webcam app

4. scroll down to bottom than click on **start server** button
 
5. From `using_wifi` folder open [this notebook](https://github.com/ravirajsinh45/connect_mobile_camera_with_computer_using_python/blob/master/using_wifi/take_mobile_camera_input_using_IPWebcam.ipynb) and follow along.

## For Ios devices
### Using Droidcam app
Update soon




# Thank you:)

