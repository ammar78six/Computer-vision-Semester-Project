# Computer-vision-Semester-Project
Computer vision Semester Project


We decided to take on the following approach:

1)Use machine learning to detect objects and separate them
2)Text Recognition to find object labels from a distance and detect if this is the product desired or not
There were a few issues along the way. Since we wanted to find products as a whole, rather than the text matches only, we had to involve mathematics in most of our algorithms. One of the algorithms was entirely on screen graphics, such as to make sure that the products detected contained the entire text boxes and that they were appropriately scaled on different resolutions.

Another issue that we faced was the lack of clear images. This required another algorithm for measuring the distance to an object using the image retrieved from the camera. Here we once again had to make use of our ML model and the object boxes to make sure that the user would position him/herself at a distance where all of the objects in the screen were comprehensible.

The indicators include : "Unsafe" for large distances and even if some objects are out of range, "Normal-Mid" for 70%-80% detection chances (optimal) and "Crystal Clear" for best results.

Once objects are detected, texts within them are drawn on the screen and a the objects are made virtually accessible by clicking on them and deriving their descriptions listed on.

The user can find any product in the shelf that matches with the descriptions they have provided in the application. This is marked in a 'bold pink' color on the screen.

Our detection algorithms have the capability to allow almost any user to find far-away shelf objects as well as to be integrated in self-assisting robots that can position themselves based upon our indicators and find products. 

TO USE
Simply fork this branch, pull it in Android Studio using VCS, build and deploy on your phone.
