# Face-and-Mask-Detection-with-mtcnn-and-Haar-Cascades

### Haar Cascades
Haar cascade is an algorithm that can detect objects in images, irrespective of their scale in image and location.  We can train a haar-cascade detector to detect various objects like face,mask,car etc.  

### How it works?
Haar cascade uses the cascading window, and it tries to compute features in every window and classify whether it could be an object.
Haar cascade works as a classifier. It classifies positive data points as that are part of our detected object and negative data points as that don’t contain our object.

### Why to Choose Haar Cascades ?
* Haar cascades are fast and can work well in real-time.
* Haar cascade is not as accurate as modern object detection techniques are.
* Haar cascade has a downside. It predicts many false positives.
* Simple to implement, less computing power required.

