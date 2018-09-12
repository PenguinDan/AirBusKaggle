# AirBusKaggle
Data Files:
* train\_ship\_segmentations.csv:
Provides the Run Length Encoded masks of ships in each image. If there are no ships, the EncodedPixel column is blank.<br>
* Columns: ImageId, EncodedPixels
* test\_ship\_segmentations.csv:
Provides the Run Length Encoded masks of ships in each image. If there are no ships, the EncodedPixel column is blank.<br>
* Columns: ImageId, EncodedPixels
sample\_submission.csv:
* Contains all of the ImageId values that should contain predictions. **EncodedPixels** should be blank if you are predicting there are no ships in the image.<br>
test:
A folder with ~88k test images, size 768x768 px <br>
There are 14 images in the Test folder that should be ignored. (Don't submit prediction for) which are the following:
['13703f040.jpg',
 '14715c06d.jpg',
 '33e0ff2d5.jpg',
 '4d4e09f2a.jpg',
 '877691df8.jpg',
 '8b909bb20.jpg',
 'a8d99130e.jpg',
 'ad55c3143.jpg',
 'c8260c541.jpg',
 'd6c7f17c7.jpg',
 'dc3e7c901.jpg',
 'e44dffe88.jpg',
 'ef87bad36.jpg',
 'f083256d8.jpg']
train:
A folder with ~104k training images, size 768x768 px
