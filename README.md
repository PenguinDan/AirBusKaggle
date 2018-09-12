# AirBusKaggle
## Table of Contents
1. [Data](#data)

<a name="data"></a>
## Data
1. train\_ship\_segmentations.csv:
* Provides the Run Length Encoded masks of ships in each image. If there are no ships, the EncodedPixel column is blank.
* Columns: ImageId, EncodedPixels
2. test\_ship\_segmentations.csv:
* Provides the Run Length Encoded masks of ships in each image. If there are no ships, the EncodedPixel column is blank.
* Columns: ImageId, EncodedPixels
3. sample\_submission.csv:
* Contains all of the ImageId values that should contain predictions. **EncodedPixels** should be blank if you are predicting there are no ships in the image.
4. test:
A folder with ~88k test images, size 768x768 px 
There are 14 images in the Test folder that should be ignored. (Don't submit prediction for) which are the following: <br>
\['13703f040.jpg', <br>
 '14715c06d.jpg', <br>
 '33e0ff2d5.jpg', <br>
 '4d4e09f2a.jpg',<br>
 '877691df8.jpg',<br>
 '8b909bb20.jpg',<br>
 'a8d99130e.jpg',<br>
 'ad55c3143.jpg',<br>
 'c8260c541.jpg',<br>
 'd6c7f17c7.jpg',<br>
 'dc3e7c901.jpg',<br>
 'e44dffe88.jpg',<br>
 'ef87bad36.jpg',<br>
 'f083256d8.jpg'\] <br>
5. train:
A folder with ~104k training images, size 768x768 px
