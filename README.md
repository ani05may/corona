# corona
This is an example of an interactive Python console script running in an Android app using Chaquopy.

The  Python script is in app/src/main/python/main.py. 
The Android activity which hosts it is in app/src/main/java/com/chaquo/python/console/MainActivity.java.
The Chaquopy configuration is in app/build.gradle.

So what i have done is created a script in python that fetches live result from mhrd.gov.nic about coronavirus count state wise.
Then i have created a table displaying it. I can add various plots using matplot to show detailed analysis.
Then next phase was to either use a web framework or android. I have tried to use android. So i have a plugin named chaquo that
helps to integrate python scripts on android. So this is how i am trying to make an app. The latter part is undergoing the development phase.
