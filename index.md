# Biometric Attendance System
<!---Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!-->

<!---You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML -->
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
<!---```-->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Nathan C | Archbishop Mitty High School | Biomedical Engineering | Incoming Junior

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**-->

![Headstone Image](logo.svg)
  
<!---# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE-->



# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/MZYSwUL4E3I?si=NHDFu7paFsT9TZGs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
My project is the Biometric Attendance system. What I have accomplished since my first milestone was adding the RTC module and the fingerprint scanner. They contribute to my final goals because the RTC also known as Real Time Clock Module allows the system to know when the person registers their fingerprint and when they check back in. The fingerprint scanner is what captures the images of fingerprints and places it in the database which is important for the project. The most suprising part of this project so far has been the coding, attaching the components wasn't that complicated after understanding how a breadboard, arduino, and jumperwires work. The coding however, has been the most challenging part of this proejct because I'm new to the arduino coding language and debugging and syntax have been the most troublesome. However, I overcame this challenge through referencing to other pieces of code and understanding what commands and functions do and I ultimately debugged and corrected my original code to reach my second milestone. What needs to be finished before the final milestone, is adding the buzzer and led light to indicate certain actions so there are other alerts besides the text on the LCD. I also have small bugs in the project that need to be fixed up still before the third milestone. 

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/omOlW2Dj-kw?si=UUPPxU9lnppjX9Y8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
The project that I chose was the Biometric Attendance System . The different components that I used for this project were the Arduino Uno, a breadboard, a LCD, jumperwires, buttons, resistors, a buzzer, and a LED. My milestone was to learn how the ciruit works and how the Arduino connects to the breadboard. Since I wanted to first grasp the concept of the connections and make sure that all my parts work, my milestone was to have the buttons display messages on my LCD screen. Throug working on this milestone, I went through many challenges with the buttons and the LCD. The LCD was a challenge to connect because each part of the LCd had to go to a specific part or else the LCD would have energy past its threshold making it not work. Connecting the buttons were also a challenge because it needed to be connected to the 5V power source, the GRN source and a pin on the Arduino, so making the four buttons fit compactly on the board was a challenge. Since I aimed to do everything at once with this milestone, I learned to isolate the problem and to do things step by step and to make sure that all steps worked properly before moving on to the next one. My plan to complete this project is to continue that strategy that I learned and to take things step by step instead of plugging everything in at once and hoping that it works. For my next milestone I'll focus first on the fingerprint scanner and getting that to take in data correctly.  


<!---# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```-->

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino UNO| The Arduino is used for connecting everything of the circuit together, providing power ot the breadboard and other components, and responsible of taking inputs and sending outputs through its microcontroller | $27 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6?crid=6LAEYX0GW2YS&keywords=arduino+uno&qid=1670424142&sprefix=arduino+uno,aps,93&sr=8-1-spons&psc=1&smid=AA57DDZKZUZDL&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExUEpBQjY0VFAwMEE5JmVuY3J5cHRlZElkPUEwMjQxNTk5MldZVExZVUVaV0dPMyZlbmNyeXB0ZWRBZElkPUEwOTQ2MzM3TldERlZJRlBETEtRJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ%3D%3D&linkCode=sl1&tag=howtoelect0e4-20&linkId=82cb8c219f6c8dfd4617f7ef8a53aed1&language=en_US&ref_=as_li_ss_tl"> Link </a> |
| R307 Fingerprint Sensor | The Fingerprint Sensor is used for taking images and scanning fingerprints and sending them back to the microcontroller on the Arduino | $17 | <a href="https://www.amazon.com/Fingerprint-Optical-Control-Attendance-Recognition/dp/B07SFYDM4M?crid=3FOXY42SAF4FT&keywords=r307&qid=1670424291&sprefix=r307,aps,92&sr=8-2&linkCode=sl1&tag=howtoelect0e4-20&linkId=eec25467d9df21024ef7f178ebd9ae74&language=en_US&ref_=as_li_ss_tl/"> Link </a> |
| DS3231 RTC Module  | The RTC Module is used for allowing the Arduino to know the time in the real world| $12 | <a href="https://www.amazon.com/HiLetgo-AT24C32-Arduino-Without-Battery/dp/B00LX3V7F0?crid=1QQNBAPK3XO9G&keywords=ds3231&qid=1670424321&sprefix=ds3231,aps,89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyNTRJRzNJUktYUVFPJmVuY3J5cHRlZElkPUEwNzQzNDg0M1BKSFZNRDRXNkEwNyZlbmNyeXB0ZWRBZElkPUEwMzA3MDIxMllBTTVSNE5LTUdNMiZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU%3D&linkCode=sl1&tag=howtoelect0e4-20&linkId=22b7c43bba77801d4153e6844a8934b6&language=en_US&ref_=as_li_ss_tl"> Link </a> |
| 16 x 2 LCD Display| The LCD is used for displaying the outputs that the Arduino gives after the inputs are given | $10 | <a href="https://www.amazon.com/HiLetgo-Character-Backlight-MEGA2560-Raspberry/dp/B079M3GWFG?keywords=16x2+lcd+display&qid=1670424064&sprefix=16x2+lcd,aps,92&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExQUlTNkQ3NkVRNVYwJmVuY3J5cHRlZElkPUEwNTQ4ODM2SlRETUJPQVJMT1NPJmVuY3J5cHRlZEFkSWQ9QTAyNzc2OTRTTUxYSldYN1BVQ0Umd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl&linkCode=sl1&tag=howtoelect0e4-20&linkId=15600955d73d19e66549c66ead8ebf02&language=en_US&ref_=as_li_ss_tl"> Link </a> |
| Potentiometer | The Potentiometer is used for controlling the amount of current flowing on certain parts of the breadboard so nothing gains more voltage than it can maintain | $9 | <a href="https://www.amazon.com/HiLetgo-Single-Joint-Potentiometer-Variable-Resistors/dp/B00MCK7JMS?keywords=10k%2Bpotentiometer&qid=1670424029&sprefix=10k%2Bpo%2Caps%2C96&sr=8-2-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyN0VNVUFKUzExOUdTJmVuY3J5cHRlZElkPUEwNTIyMDc3MTZTNk4yQVNPNEs5SyZlbmNyeXB0ZWRBZElkPUEwOTc1NDM5MzU0WEVEMEw2REtWJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ%3D%3D&linkCode=sl1&tag=howtoelect0e4-20&linkId=8c7a6d802a5d9d1f34e62928b7a14bcb&language=en_US&ref_=as_li_ss_tl&th=1"> Link </a> |
| Push Buttons | Push Buttons are used to send signals to the digital pins of the Arduino | $5 | <a href="https://www.amazon.com/Momentary-Terminal-Pushbutton-Breadboard-Electronic/dp/B09R3ZPWJ7?keywords=tact%2Bpush%2Bbutton%2Bswitch&qid=1670424237&sprefix=tact%2Bpush%2Caps%2C93&sr=8-1-spons&smid=A14FP9XIRL6C1F&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFHOUs1SzRQOVZXNE8mZW5jcnlwdGVkSWQ9QTA4ODQxMzYxSEM1R1QxRktaR1hIJmVuY3J5cHRlZEFkSWQ9QTAzMTY3MDYyWDVWQlFLWkFFWjJUJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ%3D%3D&linkCode=sl1&tag=howtoelect0e4-20&linkId=eefa107ce5444ff1c6342bcd3ad98ceb&language=en_US&ref_=as_li_ss_tl&th=1"> Link </a> |
| Buzzer 5V | The Buzzer is used to display noise output from the Arduino| $7 | <a href="https://www.amazon.com/Cylewet-Electronic-Magnetic-Continuous-Arduino/dp/B01N7NHSY6?crid=2KBK9BMQSB1CQ&keywords=buzzer+5v&qid=1670424263&sprefix=buzzer+5v,aps,98&sr=8-3&linkCode=sl1&tag=howtoelect0e4-20&linkId=39b1a4d117b8de65c554f8251f10c87b&language=en_US&ref_=as_li_ss_tl"> Link </a> |
| LED 5mm Any Color | The LED is used to display light output from the Arduino| $5 | <a href="https://www.amazon.com/MCIGICM-Circuit-Assorted-Science-Experiment/dp/B07PG84V17?crid=17WKNNY2U01ZR&keywords=led%2B5mm&qid=1670423887&sprefix=led%2B5mm%2Caps%2C95&sr=8-3&linkCode=sl1&tag=howtoelect0e4-20&linkId=d8a62fcc652a3be76fe65e94258292b9&language=en_US&ref_=as_li_ss_tl&th=1"> Link </a> |
| Connecting Wires | The Connecting Wires are used to link everything from the breadboard to the Arduino pins and allows currents to flow through them and provide power | $7 | <a href="https://www.amazon.com/EDGELEC-Breadboard-Optional-Assorted-Multicolored/dp/B07GD2BWPY?crid=H7TZFJO1QGTK&keywords=jumper%2Bwires&qid=1670423829&sprefix=jumper%2Bwires%2Caps%2C96&sr=8-1-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFKVFBCTEpDVEoxSEUmZW5jcnlwdGVkSWQ9QTA0NDg2ODAyN0RGWVlJU1VDREREJmVuY3J5cHRlZEFkSWQ9QTA5NDU0MzYxSkE3VExKQkZEQUxaJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ%3D%3D&linkCode=sl1&tag=howtoelect0e4-20&linkId=fb9cb1bfdb1eac87858ef96885bb79f0&language=en_US&ref_=as_li_ss_tl&th=1"> Link </a> |
| Breadboard | The Breadboard is used to allow current to flow so that all the parts on the breadboard can be powered and work properly  | $8 | <a href="https://www.amazon.com/Breadboards-Solderless-Breadboard-Distribution-Connecting/dp/B07DL13RZH?crid=6T9E1ZJ0A1ZJ&keywords=breadboard&qid=1670423851&sprefix=breadboard,aps,109&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyMVFBN003NDcwMzhDJmVuY3J5cHRlZElkPUEwNjI2OTk4MjRPNVBNVE5TNEdNRiZlbmNyeXB0ZWRBZElkPUEwNzgyNTA2Mzk3RkFTTTg1Qk9INSZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU%3D&linkCode=sl1&tag=howtoelect0e4-20&linkId=019fbb8879193ec4d27cdb1a71084734&language=en_US&ref_=as_li_ss_tl"> Link </a> |


<!---# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)-->


# Starter Milestone 

<iframe width="560" height="315" src="https://www.youtube.com/embed/OumJj49xcUI?si=kpIN3PI6h_-X1IId" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The starter project that I chose was the Retro Arcade. The different components that I used for this project included multiple buttons, buzzers and display screens that I had to solder onto the board. The chip and the board contained most of the code, so in order for the project to work, everything had to be solder and connected properly. On the technical aspect I learned how to solder and to fix my mistakes through  de-solder using the pump and wick. One of the challenges that I faced in this project was being very accurate and precise with soldering, the reason why is because soldering joints that aren't supposed to be together causes a short within the system and doesn't allow the project to work. Since the gaps between each joint was very small, it required precise soldering and fixing and cleaning up all the gaps was one of the biggest challenges for me. I look forward to improving my soldering in my future projects and to hopefully make less mistakes with it.
<!---To watch the BSE tutorial on how to create a portfolio, click here.-->
