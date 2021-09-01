# CSE_803

## Objective
### The objective of this project is to allow you to experience the entire process of developing a practical computer vision system, which includes data collection, manual labeling, algorithm design, code development for both training and testing, performance evaluation, etc. Although one obvious goal is to achieve higher recognition accuracy, being able to observe how each step in the development pipeline affects the final performance is equally important.

## Description
### As the low cost imaging devices, such as smartphone cameras and digital cameras, become increasingly popular, more and more applications are being developed to make use of these devices for better quality of life. In this project, you will develop a software system to automatically recognize the typical meals in your daily life from images. Examples of meals can be salad, hotdog, French fry, burger, apple, banana, bread, pizza, etc.

## Development tasks
* Data collection: you need to collect your own image database, for both training and testing. Once you decide the list of objects (types of meal) in your system, you may take as many images as possible using any camera for each meal type, which allows you to use part of them for training and the remaining for testing. If you wish, feel free to simplify the problem by placing the meal on an easy-to-segment background.
* Manual labeling: for both training and testing images, you need to provide a manual label for the meal type, which can be as simple as storing images in the separate folder named by the meal type. If necessary, you may choose to label the location of object of interests in the training images. However, for the testing images, the localization of the meal, if required by your system, should be estimated automatically.
* Algorithm design: in the training stage, you need to perform feature extraction for each image. You may learn a classifier from feature vectors of training images, or imply use a nearest neighbor classifier. In the testing stage, you need to perform object detection/segmentation and follow by recognition, or use a non-segmentation-based recognition method. You may choose to re-use some of your implemented modules in the homeworks.
* Code development: you are free to choose either Matlab or C/C++ for implementation. If it is C/C++, please compile it and include the EXE file in the final package.
* Performance evaluation: you need to measure the system performance in terms of both accuracy and efficiency. You can assume this to be a close-set recognition problem, i.e., each testing image belongs to one of the class in the training set, or an open-set recognition problem, i.e., there is one additional class for unknown objects. For accuracy, you should compute the recognition rate of each class. For example, for the apple class, the recognition rate is defined as 0.5*(# of apple images correctly recognized as apple/# of testing apple images + # of non-apple images correctly recognized as non-apple/# of testing non-apple images). For efficiency, you should record the average time (in seconds) to recognize one image.

## Requirement
* Three students form a team for work on the problem together. Three of you should partition the tasks and work together as much as possible for the best outcome. For example, frequent meeting and discussion among three of you are highly recommended. This is a great opportunity to learn from each other. You may discuss ideas and algorithms with other teams. However, sharing codes with members in other teams is NOT allowed.
* You are expected to spend sufficient amount of time to work on the project due to a) this project contributes to 25% of the final grade; b) two students work on one project; c) some of the modules have been done in prior homework. Please read the next section on
where you could make the efforts.
