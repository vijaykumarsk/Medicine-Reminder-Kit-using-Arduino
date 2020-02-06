# Medicine-Reminder-Kit-using-Arduino
INTRODUCTION:
Modern medicine is helping to live a long life comfortably. Medicines satisfy the priority health care needs of the population and modern technologies are being supported to find diseases very early so that doctors can take correct path immediately [1]. People take medicines to fight illness, to feel better when they're sick, and to keep from getting sick in the first place. So, a lot of people have to take certain medicines regularly especially those with certain specific health care issues. Programmed medication update is clever plan to help the patient to take as much time as is needed and consequently may lessen an opportunity to recoup from their malady. Here and there, the matured patient takes the wrong drug and their wrong measurement mistakenly causing the serious issue [2]. This framework isn't only useful for an individual but can likewise have significant commitment in doctors’ facilities. 

The number of inhabitants in individuals is expanding quickly, and they create memory challenges. They may miss medications, or take overdoses. This project act as a solution to this problem of medicine reminding.

ABSTRACT:

This project is a system which helps in medication administration and monitoring. Patients either forget to take the medicine at the required time or forgets which medicine to take at required time and it is difficult for a third person to monitor patients around the clock. To avoid these problems and human efforts, we have come up with this Medicine Reminder Kit using Arduino.
This system can remind patients to take medicines 1 or 2 or 3 times a day. The time slot can be selected using push buttons. Also, it shows current Date and Time. SMS notification will be sent to user.
RTC DS3231 module is interfaced through I2C protocol with Arduino Uno for time-keeping. RTC IC DS1307 can also be used for reading the time with Arduino but RTC DS3231 also has inbuilt 32k memory which can be used to store additional data. RTC module is powered through the 3.3V pin of Arduino uno. 
A 16x2 LCD display is interfaced using SPI. A buzzer is used to alert and remind that it’s time to take medicine. The logic for the processing is built into the embedded program to initiate the alert through an audio alarm. Not only does it have an alarm system, but also an LCD which displays the medicine to be taken at the reminder time.
Four push buttons are used where each has distinct select feature. The first push button is used for reminding to take medicine once per day. The second push button is used to remind twice per day and the third push button is used to remind thrice per day. The fourth push button is used to stop the buzzer when user has heard the alert.
This system is powered using 5V supply. When it first boots up, it shows a welcome massage. The LCD screen is set to cycle in three screens. The 1st screen shows massage as Stay Healthy, Get Well Soon. The second screen is a help screen which tells to press select push button to select any one time-slot to remind (once/twice/thrice in a day). The time slot is changeable in program and can be configured accordingly. 
Time slots are divided into three modes. Mode 1 selects to take medicine once/day at 8am when user presses 1st push button. Mode 2 selects to take medicine twice/day at 8am and 8pm when user presses 2nd push button. Mode 3 selects to take medicine thrice/day at 8am, 2pm and 8pm if user presses 3rd push button.

COMPONENTS REQUIRED:
1.	Arduino Uno 
2.	RTC DS3231 module
3.	16x2 LCD Display
4.	Buzzer
5.	Breadboard
6.	Push Buttons
7.	10K,1K Resistors
8.	Jumper Wires

REFERENCES:
[1] J. Pineau, M. Montemerlo, M. Pollack, N. Roy, and S.Thrun, “Towards robotic assistants in nursing homes: Challenges and results,” Robotics and Autonomous Systems, vol. 42, 2003, pp. 271-281.

[2] Aditya Vijay, Durgesh Kumar Poornima College of Engineering, Jaipur, Rajasthan and Asst. Professor, Poornima College of Engineering, Jaipur, Rajasthan “Automatic Reminder Using Arduino” April 2018| IJIRT | Volume 4 Issue 11 | ISSN: 2349-6002

[3] https://www.elprocus.com/rtc-dc1307

[4] https://www.hackster.io/TechnicalEngineer/medicine-reminder-using-arduino-dad47d

[5] https://www.electronicwings.com/anduino/hc-05-bluetooth-module-interfacing-wih-arduino-uno

[6] https://www.electroniclininc.comandroid-app-development-to-control-arduino-over-bluetooth-using-android-studio
 
[7] https://www.electronicshub.org/arduino-ds3231-rtc-module-tutorial
