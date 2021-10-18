# Voice-Controlled-Home-Automation

ABSTRACT
Automation is a trending topic in the 21st century making it play an important role in our daily lives. The main attraction of any automated system is reducing human labour, effort, time and errors due to human negligence. With the development of modern technology, smart phones have become a necessity for every person on this planet. Applications are being developed on Android systems that are useful to us in various ways. Another upcoming technology is natural language processing which enables us to command and control things with our voice. Combining all of these, our paper presents a micro controller-based voice-controlled home automation system using smartphones. Such a system will enable users to have control over every appliance in his/her home with their voice. All that the user needs is an Android smartphone, which is present in almost everybody’s hand nowadays, and a control circuit. The control circuit consists of an Arduino Uno microcontroller, which processes the user commands and controls the switching of devices. The connection between the microcontroller and the smartphone is established via Bluetooth, a widespread wireless technology is used for sharing data.

Keywords: Arduino Uno, HC-05 Bluetooth Module, Home Automation, Smartphone, Voice Control.

INTRODUCTION

The foremost aim of technology has been to increase efficiency and decrease effort. With the advent of ‘Internet of Things’ in the last decade, we have been pushing for ubiquitous computing in all spheres of life. It thus is of extreme importance to simplify human interfacing with technology. Automation is one such area that aims to achieve simplicity whilst increasing efficiency. Voice controlled House Automation System aims to further the cause of automation so as to achieve the goal of simplicity.
The primitive man realized that an effective way to communicate with one another is through voice. With minimum effort, ideas could be narrated with relative ease. When the first computers came around, achieving the level of sophistication so as to narrate commands using voice to a machine was only realized in science fiction. However, with tremendous breakthroughs in the field, we are at the precipice of truly using voice to interface with devices. Using this effective yet ingrained form of communication we would humanize technology to a great extent. Voice controlled Home Automation System deploys the use of voice to control devices. The advantages of using voice as an interfacing medium are multi-fold. Firstly, we would do away with or significantly decrease the need of training for operating technology. Secondly, the simplification of services would entail a wider adoption of existing technology and would help people with varied disabilities access the same technology. We have deployed an Android Application as user front end primarily because of the ease at which the platform provides us means to use complex technology and due to the widespread adoption in the mobile industry. Android is being used as the operating system for over 80% of the smartphones. Voice controlled House Automation System leverages the power of Arduino to provide a holistic voice-controlled automation system. Using Natural Language Processing and the available hardware in most smartphones, it translates voice to be used for controlling electrical devices.

PROPOSED METHOD
Block diagram

![image](https://user-images.githubusercontent.com/43086002/137742024-0a09fd5c-e82c-40e7-ad92-fb999f677948.png)

COMPONENTS
• Android based mobile phone
• Bluetooth module
• Arduino uno
• IR sensor
• Electronic appliances

FLOW DIAGRAM

![image](https://user-images.githubusercontent.com/43086002/137742108-fc98b6a1-09db-4b0a-b7bf-ef0b717f7f25.png)

IMPLEMENTATION
Using the above-mentioned components, we implement our system on a breadboard. The microcontroller device with the Bluetooth module and electronic components needs to be 
attached with the switch board. Then we need to launch the android based application on our Smartphone. Through the application we can instruct the microcontroller to switch on/off an appliance. After getting the instruction through the Bluetooth module the microcontroller gives the signal to the requested electronic appliance. The application first searches for the Bluetooth device. If it is available then it launches the voice recognizer. It reads the voice and converts the audio signal into a string. The microcontroller uses the port in serial mode. After reading the data it decodes the input value and sends a signal to the parallel port through which the circuit will be activated. We can also regulate all devices in a single instruction. In this work we use Bluetooth module. We can also attach a GSM module to do the work, using which the application can be used anywhere where a mobile network is available.We have also deployed an IR sensor to sense the presence of people in a room and regulate the lights accordingly.

![image](https://user-images.githubusercontent.com/43086002/137742295-833dfce0-2f2e-4ac1-9c7e-9394f908d520.png)

![image](https://user-images.githubusercontent.com/43086002/137742317-f81ac9a1-55db-4966-b7cc-cb23855666a0.png)

![image](https://user-images.githubusercontent.com/43086002/137742356-db686757-00b0-4dd1-8b80-0332c5b5b9bb.png)

CONCLUSION

The proposed project undertakes a viable solution the need of automation at the very basic level, that is, in our homes. The project will enable us to bring every appliance at every corner of our home under our control from a single point without having to get up and manually switch on or off the appliance. The use of a Bluetooth module assists the use of this system from various locations in our house. The system is further simplified by allowing appliances to be controlled by our voice. The user need not have to have to immense knowledge over the language of English. Just by saying the appliance name and the corresponding number assigned to that particular appliance, and telling it to switch on or off will enable the user to have complete control over any appliance without any effort. Android applications are very simple and user friendly allowing the user to understand its functionalities in very little time. Hence, the use of android application in this system allows a user to easily learn the process and get accustomed to the functions. Moreover, the entire system is very flexible and scalable. Any number of appliances can be added as and when required. Hence, the systems find use not only 
in houses but also in many offices where appliances such as fans or lights on multiple floors can be controlled by a person on any of the floors, saving manual labour and human effort to switch on or off the electronic appliances, thereby saving time. This system, though primarily aimed to reduce human effort, will be of much importance to old aged people and physically handicapped people. It will enable them to control their home devices with ease, without going through much pressure or stress of moving about. Due to the inexpensive materials used in the construction and further cost optimization if the device is taken to the market, it finds application in a wide area. Scalability of the project would be considerably easier as the device can be used in every building using electrical appliances and devices. In addition, there have been many advertisements broadcasted by the Government of India promoting awareness to switch off household appliances when not in use and thus save electricity. Hence, such a project would assist the initiatives taken by the government, as most people forget to switch off home appliances and are too lazy to return and switch it off. Also, gauging the currently ongoing pandemic, we can implement this system in all public places such as stations, airports, offices, restaurants and gymnasiums. This will allow us to maintain social distancing and avoid physical contacts with the conventional switches and devices, which could be contaminated.


