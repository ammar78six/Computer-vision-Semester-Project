# Computer-vision-Semester-Project
Computer vision Semester Project


We decided to take on the following approach:

1)Use machine learning to detect objects and separate them

Issue that we faced was the lack of clear images. This required another algorithm for measuring the distance to an object using the image retrieved from the camera. Here we once again had to make use of our ML model and the object boxes to make sure that the user would position him/herself at a distance where all of the objects in the screen were comprehensible.

The indicators include : "Unsafe" for large distances and even if some objects are out of range, "Normal-Mid" for 70%-80% detection chances (optimal) and "Crystal Clear" for best results.

Once objects are detected, texts within them are drawn on the screen and a the objects are made virtually accessible by clicking on them and deriving their descriptions listed on.

Our detection algorithms have the capability to allow almost any user to find far-away shelf objects as well as to be integrated in self-assisting robots that can position themselves based upon our indicators and find products. 

TO USE : 
Simply fork this branch, pull it in Android Studio using VCS, build and deploy on your phone.
