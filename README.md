# Android Tv Live Stream

Developer: <b>SAAD</b> <br>
Email: saad@triangeltech.com<br>
Website: https://engr-saad.com <br>
LinkedIn: https://www.linkedin.com/in/raselhasandurjoy<br>
Facebook: https://www.facebook.com/developer.saad<br>
Company WEB: https://triangeltech.com/ <br>
Phone: +8801904654712<br>

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=102)](https://github.com/raselhasandurjoy/Android-TV-Live-Stream)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

A sample app for Android TV written in Java that utilizes the KenticoCloudDeliveryJavaRxSDK to manage and retrieve content You can register your account for free at https://app.kenticocloud.com...

By default, it displays content from a Sample Project that demonstrates Kentico Cloud features and best practices. This fully featured project contains marketing content for Dancing Goat – an imaginary chain of coffee shops. If you don't have your own Sample Project, any admin of a Kentico Cloud subscription can generate one.

## Application Setup 
Install Android Studio and the latest Android SDK tools.<br>
Clone or download the repository into a chosen folder..<br>
Open the project in the IDE, let it install all the necessary libraries and tools.<br>
Create a virtual TV device, for example with specifications 1080p, and Android API 25.<br>
Run the project witht the created TV device as a specified deployment target<br>

## Content Administration 
Navigate to https://app.kenticocloud.com in your browser.<br>
Sign in with your credentials.<br>
Manage content in the content administration interface of your sample project.<br>
You can learn more about content editing with Kentico Cloud in the documentation.<br>

## Content Delivery
In order to utilize your own project instead of the default one, you need to change the KENTICO_CLOUD_PROJECT_ID constant in the AppConfig.java file to the ID of your own project.<br>
The project ID can be found on Kentico Cloud by navigating to Project Settings and then to API Keys
Application Installation<br>
Building the project in Android Studio creates an .apk file, located in app\build\outputs\apk\debug.<br>

The file can be used to install the application on a TV, using the Android Debug Bridge..<br>

The Developer Mode and Allow USB debugging modes have to be turned on the TV<br>

#### By connecting the laptop and the TV with a USB cable and having both of them on the same network, one can install the app:

adb connect <TV_IP_ADDRESS><br>

adb install <PATH_TO_.APK_FILE><br>

The TV has to be connected to the Internet in order to retrieve content from Cloud.

