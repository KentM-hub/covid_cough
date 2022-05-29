# Covid Cough

![](https://img.shields.io/badge/code_size-2.51GB-blue&style=plastic)

> Press the record button to find out if you are infected with covid-19.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Feature](#feature)
* [Screenshot](#screenshot)
* [Room for Improvement](#room-for-improvement)


<!-- * [License](#license) -->


## General Information
- This application uses a teaching machine to learn the cough sounds of covid-19  and non-covid-19 patients and determines if you are infected with coronavirus or not by the sound of your cough.

- I created this application because I felt that there were few means to easily determine if a person was infected with coronavirus without human contact.

- I have collected cough data from [this site](https://github.com/virufy/virufy-cdf-coughvid/tree/main/virufy-cdf-coughvid)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Flutter](https://flutter.dev/?gclid=CjwKCAjwkMeUBhBuEiwA4hpqEIwDDWSKdwDOQ3uX2aeZWf1CLOHk4kX9ghhdG94K2VmGJx3-4h8gChoCjG8QAvD_BwE&gclsrc=aw.ds) - version 3.0.1
- [tflite_audio](https://pub.dev/packages/tflite_audio) - version 0.3.0
- [Teachable Machine](https://teachablemachine.withgoogle.com/)


## Feature
- Tap the microphone button at the bottom of the screen to record the sound of your own cough, and you will know in real time whether you are infected with the coronavirus.


## Screenshot
![Example screenshot](/assets/example.png)
<!-- If you have screenshots you'd like to share, include them here. -->



## Room for Improvement
Accuracy is still considered lacking due to the paucity of coughing data from people not infected with coronavirus.

Room for improvement:
- Increase the number of coughing data to improve accuracy.
- Change to a more understandable user interface.






<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->