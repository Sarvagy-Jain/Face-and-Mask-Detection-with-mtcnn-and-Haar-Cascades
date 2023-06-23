# Face-and-Mask-Detection-with-mtcnn-and-Haar-Cascades
Haar cascade is an algorithm that can detect objects in images, irrespective of their scale in image and location.  We can train a haar-cascade detector to detect various objects like face,mask,car etc.  
Haar cascade uses the cascading window, and it tries to compute features in every window and classify whether it could be an object.

<p align="center">
![Cascades](https://github.com/Sarvagy-Jain/Face-and-Mask-Detection-with-mtcnn-and-Haar-Cascades/assets/82312885/d8cff185-f1b3-4769-aa7a-b54fe285e888)
</p>

Haar cascade works as a classifier. It classifies positive data points → that are part of our detected object and negative data points → that don’t contain our object.

*Haar cascades are fast and can work well in real-time.
*Haar cascade is not as accurate as modern object detection techniques are.
*Haar cascade has a downside. It predicts many false positives.
*Simple to implement, less computing power required.

