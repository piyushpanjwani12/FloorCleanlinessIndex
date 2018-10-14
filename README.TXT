-> The technology used is Opencv with java

-> The input images are given.(f1.jpg, f2.jpg) / (flr1.jpg, flr3.jpg), etc) For calculating the index, we need references. The jar file initially requires a reference image 1.) Image of a clean flower(let "f1.jpg"). Then using this image, a reference is made. For calculating the cleanliness, a new image is put in the software, and the cleanliness of the floor in it is is calculated and presented.

-> The output is generated in the form of a slider. Also a cleanliness percent is reported.

->The source code is present in the src folder. It consists of the complete code and the opencv library.

-> Instructions to deploy and run
1. Paste the "opencv_java2411.dll" file in the system32 folder of your computer.("C:\Windows\System32")
2. Now run the FloorCleanlinessIndex.jar file.
3. Now enter the name of the clean flower image.
click submit.
4. Now enter a random floor image(of a similar kind of floor) to check the cleanliness index.
5. You can test the code using the (f1.jpg, f2.jpg) / (flr1.jpg, flr3.jpg) / (ff1.jpg, ff2.jpg) / (fff1.jpg, fff2.jpg) image pairs are given in the repository.
6. The dll file mentioned above is important to be uploaded in the system32 folder.
