# Ping and Track

Ping and Track, an android based application for tracking the location of a lost android device using SMS. The application locates device by sending a SMS to lost android device and in return receives the lost android device’s latitude and longitude. The application also provides the feature to block certain numbers at the lost android device’s end thus preventing the blocked users from receiving the lost android device’s location details.The Android Application is well suited for android devices having calling features. The seeking device registered in the database of the lost android device sends a SMS (which is a predefined attention word) to the lost android device (device whose location is to be tracked); the application then matches the contents of the SMS with the predefined attention word. If the SMS content matches with the predefined attention word, then the application retrieves the location details of the lost android device and sends the same.

Detailed report can be found here - (https://drive.google.com/file/d/1Ro5Nrb1Cds-iquS6CvBzjq8eNz6aAdnK/view?usp=sharing)


# Screenshots
![Screenshots](https://github.com/aman33459/PingandTrack/blob/master/pingandTrackimages/1.png)

![Screenshots](https://github.com/aman33459/PingandTrack/blob/master/pingandTrackimages/3.png)

![Screenshots](https://github.com/aman33459/PingandTrack/blob/master/pingandTrackimages/3.png)


# Accuracy

We installed the Ping and Track application on a number of android devices and performed the testing operation. We found that the response time of the application was on an average 4-5 seconds. It responded each time we enquired for the lost phone’s location through SMS containing the key word, ‘GET LOCATION’.
We tested our application for different locations (approximately 100 locations) and tried to estimate the difference between the actual location of the tracked mobile and the location detected by our application. It turned out that the difference in the accuracy of the distance measurement was around 9 feet - 10 feet approximately. Hence providing an accuracy of 99.6% ((Sum of all the differences in actual location of the tracked mobile and the location detected by our application/ 100 )*100).
