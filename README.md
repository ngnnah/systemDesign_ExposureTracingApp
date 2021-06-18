# systemDesign_ExposureTracingApp
* As part of MIT's 6.033 Computer System Engineering, we (Nhat Nguyen, Veronica Muriga, and Shashvat Srivastava) designed a `phone-based exposure (contacting) tracing system` called Enhanced Exposure Exterminator (EEE)
  * `that prioritizes accuracy, timeliness, privacy and low phone impact to achieve the goal of swiftly identifying and responding to potential outbreaks on campus.`
* **Background**: every smartphone can send and receive BLE (Bluetooth Low Energy) signals that can serve as the cornerstone of modern contact tracing. An app-based exposure tracing system needs to identify infections and improve isolation compliance, while protecting user privacy. Many of the existing systems are not widely used, due to lack of trustworthiness and utility. Therefore, our system was designed with accuracy, timeliness, privacy and low computational impact being prime priorities.


## This project is the culmination of MIT Computer Science Header course 6.033, which consists of 4 modules: OS, Network, Failure, and Security. Our paper received an `A grade` which was quite rare in this course.

### Here's the Introduction from Our system design paper:
> Past human experience with pandemics has led to the increased demand in effective contact tracing and exposure notification systems, to mitigate the spread of infectious diseases by identifying people who have been in close enough contact with infected people. In this digital era, smartphones have the power to serve as the cornerstone of modern contact tracing systems, by leveraging technologies such as Bluetooth Low Emission (BLE) transmissions and WiFi. A contact tracing and exposure tracing system needs to identify infections and improve isolation compliance, while protecting user privacy. Analysis of historical contact tracing systems showed that they all faced some success, but with significant challenges in uptake due to privacy concerns, inability of EEEs to scale up to accommodate a large number of users, and lack of universal access to smartphones. In this paper we propose an app-based contact tracing system for a university similar in size to MIT, that prioritizes accuracy, timeliness, privacy and low phone impact to achieve the goal of swiftly identifying and responding to potential outbreaks on campus.

* An overview diagram of the system that I made:
<img src='https://user-images.githubusercontent.com/58123635/122488584-c36d2780-cfab-11eb-829c-011af253ade5.png' height='450px' />
