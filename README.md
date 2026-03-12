FM RADIO BASED ALARM CLOCK WITH RGBs

BECE304L –
Analog Communication Systems


Course Based Project
Bachelor of Technology in
Electronics and Communication
By
Zeeshan Ahmad (23BEC0237) 


March, 2025
 
ABSTRACT :
The FM Radio Alarm Clock with RGB Sunrise Effect is an innovative project designed to provide a more natural and pleasant wake-up experience by simulating sunrise with RGB LEDs and playing an FM radio station at the set
alarm time. Conventional alarm clocks often cause abrupt wake-ups, which can lead to sleep inertia and discomfort. In contrast, this project gradually increases the brightness of RGB LEDs before the alarm time, mimicking natural daylight, which is scientifically proven to help regulate circadian rhythms and improve morning alertness.
The project is implemented using an Arduino Uno microcontroller, which coordinates the RGB LED dimming and FM radio activation. The TEA5767 FM radio module allows the user to tune into preset radio stations, providing a
customizable alarm sound. The DS3231 Real-Time Clock (RTC) module ensures accurate timekeeping, making the alarm system reliable. The RGB LED strip used in the project, such as WS2812B addressable LEDs, allows precise control of brightness and color. This project integrates embedded systems, wireless communication, and human-centric design to create a cost-effective and
energy-efficient alternative to commercial sunrise alarm clocks.
Furthermore, this project demonstrates the practical applications of
microcontroller-based systems in daily life. By incorporating RTC functionality, it maintains time accuracy even during power interruptions. The use of WS2812B LEDs enables fine-grained brightness control, allowing users to create a fully customizable sunrise effect. The FM radio module ensures users can wake up to music or news broadcasts, making the waking experience more pleasant.
With the growing emphasis on smart home automation, this project aligns with the trend of integrating personalized technology into everyday routines.
 
MOTIVATION:
The motivation behind this project arises from the shortcomings of
conventional alarm clocks and the growing need for smart, user-friendly wake- up solutions. Traditional alarm clocks use sudden sound cues that can be
disruptive and stressful, leading to grogginess. Studies indicate that a gradual increase in light before waking up can align the body’s natural sleep cycle, promoting a more refreshing start to the day. Inspired by commercial sunrise alarm clocks, this project aims to offer a cost-effective, customizable, and DIY- friendly alternative.
Scientific research suggests that sudden loud noises can cause an abrupt
increase in heart rate and stress levels upon waking. This can lead to a groggy state known as sleep inertia, which negatively affects productivity and cognitive functions for a significant period after waking up. In contrast, a gradual light- based alarm helps regulate melatonin production, ensuring a smoother
transition from sleep to wakefulness. This project capitalizes on these findings by integrating an RGB LED strip that simulates sunrise.
Another key motivation is the educational value of the project. The development of this system involves integrating multiple hardware
components and programming techniques, making it an excellent learning experience for electronics and embedded systems enthusiasts. By using an Arduino Uno, the project remains accessible to beginners while allowing advanced users to modify or expand the functionality as needed.
Additionally, affordability and accessibility are major driving factors.
Commercial sunrise alarm clocks can be expensive and may lack the flexibility of FM radio integration. This project provides an open-source, budget-friendly solution, utilizing readily available components to ensure easy replication and customization. The cost-effectiveness of this project makes it feasible for students, hobbyists, and individuals looking for a DIY alternative to expensive smart alarms.
 
LITERATURE SURVEY:
To develop a well-informed and effective project, extensive research was conducted on the following key aspects: wake-up light therapy, FM radio alarm systems, and embedded system-based alarm clocks. The literature survey
examines existing studies, commercial products, and technological advancements related to these areas.
1)	Wake-Up Light Therapy :
Scientific research supports the use of gradual lighting to enhance the waking experience. Studies have demonstrated that exposure to increasing light
intensity before waking up can positively influence the body’s circadian rhythm, improving alertness and mood. The Philips Wake-Up Light and the Lumie
Bodyclock are two well-known commercial sunrise alarm clocks that utilize this principle. These devices use warm LED lighting with a gradual intensity curve to simulate a natural sunrise.
Research papers on light therapy in sleep studies suggest that exposure to
warm light before waking up can help regulate melatonin production, reducing sleep inertia. One such study published in the Journal of Clinical Sleep Medicine confirms that light-based alarms enhance cognitive performance upon waking compared to traditional alarms. This project incorporates this concept by using an RGB LED strip with gradually increasing brightness, providing a DIY
alternative to commercial wake-up lights. By controlling the brightness levels with Pulse Width Modulation (PWM) techniques, a smooth transition from darkness to bright light is achieved, simulating natural sunlight exposure.
2)	FM Radio Alarm Clocks : 
FM radio-based alarm clocks have been widely used for decades, offering an
alternative to traditional buzzer alarms. Studies in consumer electronics reveal that radio-based alarms provide a more customizable and pleasant wake-up
experience compared to beeping alarms. Products such as the Sony ICF-C1 and JBL Horizon are well-known FM radio alarm clocks that offer features like station presetting and gradual volume increase.
 
The TEA5767 FM radio module, used in this project, is a compact and efficient FM receiver that allows for easy integration with Arduino. This module
supports automatic frequency tuning and low-power operation, making it an ideal choice for battery-powered projects. Additionally, FM radio provides a variety of auditory stimuli compared to standard alarm tones, making waking up a more engaging experience. Research has shown that waking up to
preferred sounds or music can enhance mood and increase alertness compared to sudden loud alarms.
3)	Embedded System-Based Alarm Clocks :
Recent advancements in embedded systems have facilitated the development of microcontroller-based alarm clocks with added functionalities. Research on Arduino-based alarm systems highlights the use of RTC modules for precise
timekeeping, PWM (Pulse Width Modulation) for LED dimming, and I2C
communication for seamless integration of multiple hardware components.
The DS3231 RTC module, used in this project, ensures accurate timekeeping and is equipped with a backup battery to maintain functionality even during power loss. Studies on Arduino-based automation projects indicate that the DS3231 is highly reliable for alarm systems due to its temperature- compensated crystal oscillator, which minimizes time drift.
4)	Comparison with Existing Solutions :
While commercial sunrise alarm clocks and FM radio alarms exist as separate products, this project integrates both functionalities into a single DIY system. Unlike high-end commercial devices that may require firmware updates and proprietary applications, the Arduino-based implementation offers full customization, allowing users to modify the alarm time, radio station, and light intensity curves according to their preferences.
Moreover, commercial FM radio alarms typically lack gradual lighting features, relying solely on sound. This project fills that gap by combining a wake-up light with an FM radio alarm, enhancing the overall waking experience. Studies
indicate that multisensory waking experiences, such as combining light and sound, result in a more effective and less stressful transition from sleep to wakefulness.
 
5)	Gaps in Existing Research and Innovations Introduced :
Despite the availability of commercial sunrise alarm clocks and FM radio alarm clocks, there is limited research on combining these features in a single low- cost, DIY system. This project bridges that gap by offering a customizable and energy-efficient solution.
Furthermore, the inclusion of WS2812B addressable LEDs enhances the flexibility of the sunrise simulation. Unlike conventional LED bulbs used in
commercial sunrise alarms, addressable LEDs allow for smooth brightness
transitions and color variations, making the wake-up experience more dynamic and visually appealing.
Additionally, this project leverages the simplicity and accessibility of Arduino, ensuring that users from various skill levels can build and modify the system according to their needs. The open-source nature of the project allows for further development and potential integration with IoT-based applications,
such as smartphone-controlled alarms or adaptive lighting based on ambient conditions.
6)	Comparison with Alternative Wake-Up Methods
1.	Vibrating Alarms: Some smartwatches and alarm clocks use vibrations, but these may not be effective for deep sleepers.
2.	Binaural Beats and Sound Therapy: Some alarm systems use specific sound frequencies for a gentle wake-up, but they lack the physiological benefits of gradual light exposure.
3.	Smartphone Alarm Apps: While apps provide various tones and volume settings, they don’t simulate gradual lighting, and users may find it easy to snooze them.
7)	Future Enhancements Based on Research
1.	Integration of AI Algorithms: Future versions could use AI to analyze sleep cycles via wearable devices and trigger the alarm at the optimal moment in the sleep cycle.
 
2.	Customization Based on Seasons: The system could adjust brightness
levels and wake-up times according to sunrise times in different seasons.
3.	Use of White Noise or Nature Sounds: Adding soft nature sounds along with FM radio could provide a more relaxing wake-up experience.
4.	Multi-User Support: If multiple people share a room, individual alarms with personal light zones could be developed using separate LED
segments.


Proposed Method –
5.1	Timekeeping and Alarm Scheduling
A central aspect of this project is the accurate timekeeping required to trigger the alarm at a specified time. To achieve this, the RTC DS3231 (Real-Time Clock) module is used to provide accurate timekeeping, ensuring the system functions properly.
RTC DS3231 Timekeeping
The DS3231 RTC is an accurate, low-power, real-time clock module with built-in temperature compensation. The DS3231 uses I²C communication to interact with the microcontroller
(Arduino). It keeps track of the current time and date, even when the system is powered off, using its built-in battery.
●	Accuracy: The DS3231 has an accuracy of ±2 minutes per year, making it highly reliable for alarm clocks.

●	Power Consumption: The module consumes very low power, making it ideal for continuous time tracking.

●	Time Display: The DS3231 stores time in a 24-hour format (HH:MM:SS), which is crucial for setting up accurate alarm times.
 
Alarm Scheduling
Once the time is set, the alarm time needs to be configured. The Arduino will store the
alarm time in its memory, and this value will be compared to the current time tracked by the RTC. When the two values match, the system will trigger the alarm.
●	User Input: The user inputs the desired alarm time through buttons or a potentiometer, which the Arduino reads to set the alarm time.

●	Comparison Logic: The system continuously compares the current time from the DS3231 with the stored alarm time. When they match, the alarm is triggered.


5.2	Sunrise Simulation with RGB LEDs
The key feature of this alarm clock is the RGB Sunrise Simulation, which uses RGB LEDs to gradually increase the brightness of the light, mimicking the natural sunrise and making the waking experience more gradual and less jarring. This simulation helps stimulate the body's natural wake-up process by slowly increasing the intensity of light.
RGB LED Selection and Configuration
RGB LEDs were chosen for this project because they allow precise control over the colors and brightness levels using PWM (Pulse Width Modulation). The PWM signal modulates the brightness of each LED, making it possible to simulate sunrise effects.
●	LED Placement: Three RGB LEDs are used to simulate a sunrise effect. The colors are controlled by varying the red, green, and blue channels.

●	PWM Control: The Arduino uses PWM to gradually increase the brightness of the
RGB LEDs. Each LED color is controlled by an analogWrite() function, allowing for fine control over the light intensity.

●	Gradual Brightness Increase: The sunrise effect begins about 5 minutes before the set alarm time. The LEDs start from a low intensity (dimming mode) and increase gradually. This ensures the user is gently woken up with increasing light intensity, making the experience less abrupt.
 
Sunrise Simulation Logic
The logic behind the sunrise simulation involves increasing the brightness over a fixed time duration, typically 5 minutes, before the alarm triggers. Here’s the step-by-step process:
1.	Initial State: At the start of the alarm process, the LEDs are at a very low brightness level (e.g., 5% intensity).

2.	Gradual Increase: The brightness is gradually increased, typically by 5% every 30
seconds, until the LEDs reach their maximum intensity (100% brightness) just as the alarm time is reached.

3.	Color Control: The RGB channels are adjusted so that the color temperature of the light changes from a warm, reddish tone to a cool, bright white, mimicking a natural sunrise.

The code for controlling the RGB LEDs might look like this:
cpp CopyEdit
void sunriseSimulation() {
for (int brightness = 0; brightness <= 255; brightness++) {
analogWrite(RED_PIN, brightness);
analogWrite(GREEN_PIN, brightness / 2); analogWrite(BLUE_PIN, brightness / 4);
delay(200); // Delay to allow the brightness to gradually increase
}
 
}



5.3	FM Radio Activation - 
Once the alarm time is reached, the system activates the FM radio module and starts broadcasting a selected FM station. The FM radio module, in this case, the TEA5767, is controlled via I²C communication with the Arduino.
TEA5767 FM Radio Module
The TEA5767 is a compact FM radio module that can receive FM radio frequencies. It is capable of tuning to a wide range of FM stations, and it communicates with the Arduino via the I²C protocol.
●	Frequency Range: The TEA5767 supports FM frequencies in the range of 87.5 MHz to 108 MHz, covering the entire FM radio band.

●	I²C Control: The module is controlled by sending commands via I²C, allowing the Arduino to select the desired frequency.

FM Radio Control Logic
The process of tuning to a specific FM station involves sending the correct frequency value to the TEA5767 module. Once the alarm triggers, the system activates the radio and begins playing the station at the preset frequency.
1.	Frequency Selection: The user can select the desired frequency or preset station. The Arduino stores this frequency.

2.	Activation: At the alarm time, the Arduino sends the stored frequency to the FM module, and it starts broadcasting.

3.	Audio Output: The sound is sent to a speaker, providing a gentle waking sound that’s less abrupt than traditional alarms.

Example code for tuning the FM module: cpp
 
CopyEdit
radio.setFrequency(101100000); // Set the frequency to 101.1 MHz



5.4	Audio Output Control - 
To complete the waking experience, the system needs an audio output. In this case, the sound output is generated by the FM radio module and played through a speaker. The goal is to ensure that the sound is loud enough to wake the user but not too harsh.
Speaker Integration
The FM radio module outputs audio in a stereo signal, which is then connected to an amplifier to drive the speaker. The sound level is controlled through the Arduino and the radio module.
Volume Control
A key challenge is to balance the volume. The system should not start with an overly loud volume, which could cause discomfort. Therefore, the volume is set at a moderate level initially and can be adjusted by the user using buttons or a potentiometer.
●	Automatic Volume Adjustment: The volume can also be gradually increased in sync with the brightness of the RGB LEDs, creating a more natural transition from silence to sound.

●	Manual Volume Control: The user can adjust the volume before setting the alarm time.


5.5	Power Management - 
Power management is essential to ensure that the system is energy-efficient and operates reliably over extended periods. The alarm clock uses various strategies to minimize power consumption while maintaining functionality.
Low Power Consumption
●	Microcontroller: The Arduino microcontroller is powered by a 5V regulated power supply. While the Arduino is on, it consumes low power, especially when in idle
 
mode.

●	RTC Module: The DS3231 is powered by a backup coin cell battery, ensuring that the time is preserved even if the system is turned off or unplugged.

●	RGB LEDs: Since the LEDs are only turned on at the alarm time and gradually increase in brightness, their power consumption is kept low until activation.

Sleep Mode - 
To further optimize power usage, the system can enter a sleep mode when not in use, and components like the FM module can be turned off until the alarm is triggered.

5.6	Integration and Testing
Once the individual components (RTC, FM module, RGB LEDs, speaker) were designed and tested, the next step involved integrating these components into a single cohesive system. The integration phase involved ensuring that:
●	The microcontroller could correctly communicate with the RTC to retrieve time.

●	The microcontroller could control the RGB LEDs for sunrise simulation.

●	The FM radio module could be activated at the alarm time and output sound to the speaker.

Once integrated, extensive testing was carried out to ensure that all components functioned as intended, and adjustments were made to the system for better synchronization of the sunrise effect and radio alarm.

 

Explanation of Output : 
The output of the FM Radio Alarm Clock with RGB Sunrise Effect is a combination of visual and auditory signals designed to provide a natural and gradual wake-up experience. The system integrates the RGB LEDs, the FM radio module, and the RTC module to deliver an effective alarm system that mimics natural sunrise and plays an FM radio station as the
wake-up sound.
1.	RGB Sunrise Effect Output:
The key visual output of the system is the RGB LED sunrise effect. The output process begins five minutes before the preset alarm time, and it operates in the following manner:
●	Initial State (5 Minutes Before Alarm): The RGB LEDs start in a dimmed state, representing the pre-sunrise condition. The LEDs are gradually brightened as time approaches the alarm set time. This gradual increase in brightness simulates the natural rise of the sun, mimicking the sunrise effect.

●	Gradual Brightening Process: The brightness of the LEDs increases gradually. Each of the RGB LED components (Red, Green, and Blue) starts from a low value and then
gradually reaches the maximum brightness. This is controlled using Pulse Width
 
Modulation (PWM), a technique that adjusts the duty cycle of the signals sent to the LEDs.

○	Red LED starts with a low intensity and gradually increases to the maximum intensity (255).

○	Green LED starts at an even lower intensity, typically at half the intensity of the Red LED.

○	Blue LED is dimmer compared to the Green LED, starting at one-fourth of the intensity of the Red LED.

●	The intensity for each color is set in a pattern where:

○	The Red LED represents the natural warmth of the sunrise.

○	The Green and Blue LEDs provide a balanced color spectrum, gradually shifting toward daylight colors.

●	Result: After five minutes, the RGB LEDs simulate the effect of a natural sunrise, preparing the user to wake up with a soft increase in light, similar to how the sun gradually rises in the morning. The full brightness reached in these five minutes
ensures the user is gently awakened by light, creating a smooth transition from sleep to wakefulness.

2.	FM Radio Output:
At the exact time of the alarm (i.e., the preset time stored in the RTC module), the FM radio module is activated, and it starts playing the FM station set in the code. Here’s the step-by- step process for the FM radio output:
●	FM Radio Station Tuning: The TEA5767 FM radio module uses the I2C
communication protocol to interact with the Arduino. Once the alarm time is reached, the module is triggered to tune into a preset frequency. For example, the system can be set to play 101.1 MHz, but the frequency can be adjusted according to user preferences.
 
●	Audio Output via Speaker: The FM module outputs an analog audio signal to a small speaker module connected to the Arduino. This audio signal corresponds to the FM radio station the system is tuned to.

●	Sound Duration: The alarm will continue playing the FM radio until it is manually turned off or a preset duration is reached. The sound from the FM station serves as the primary alarm sound, offering a pleasant auditory experience compared to conventional alarm sounds.

●	Volume Control (Optional): The output volume can be controlled through the
Arduino, depending on how the speaker is wired. While the default output is set to a basic volume, it can be adjusted or expanded for user control, either in hardware or software.

●	Result: The user wakes up not only due to the gradual increase in light but also to the pleasant sound of their favorite FM station. This combined approach makes waking up more natural and less jarring compared to traditional alarm clocks.

3.	Combined Visual and Auditory Output:
The combination of light and sound output provides a holistic approach to waking up:
●	Visual (RGB Sunrise Effect): The RGB LEDs gradually brighten over five minutes to simulate the sunrise effect, which is scientifically known to ease the process of waking up. The gradual light transition from dim to bright ensures the body’s
circadian rhythm is in sync with the time of awakening.

●	Auditory (FM Radio Sound): Once the visual output reaches its peak brightness, the FM radio sound comes in as a gentle wake-up signal. Instead of a loud, jarring alarm sound, the user hears music or talk shows from their favorite FM station, creating a more enjoyable and peaceful waking experience.

4.	Testing and Evaluation of the Output:
The system was tested to ensure the accuracy of the time, the gradual sunrise effect, and the proper functioning of the FM radio alarm. Some important observations during testing were:
 
●	Time Accuracy: The RTC DS3231 module provided accurate time readings, and the system successfully triggered the sunrise effect and FM radio at the correct time. The time delay between the alarm trigger and the sunrise effect was precisely five minutes, as expected.

●	Brightness Levels: The RGB LEDs gradually brightened without noticeable flickering or instability. The PWM values for each color (Red, Green, Blue) were smoothly transitioned, creating a realistic sunrise effect.

●	FM Radio Activation: The FM radio module effectively tuned to the preset frequency (e.g., 101.1 MHz) and played the audio through the speaker. The system provided clear and audible sound output with appropriate volume levels.

●	User Experience: Feedback from initial testing indicated that the gradual sunrise effect paired with the FM radio alarm created a pleasant and relaxing wake-up experience, as compared to traditional alarms. The combination of light and sound helped the user ease into the day rather than waking abruptly.

 
 

Conclusion of Output Explanation:
The FM Radio Alarm Clock with RGB Sunrise Effect effectively integrates both visual and auditory outputs to create a natural and pleasant wake-up experience. The gradual increase in brightness from the RGB LEDs mimics the sunrise, helping the user transition smoothly
from sleep to wakefulness. Simultaneously, the FM radio module provides an auditory signal, playing a preset station to further enhance the waking process. The combined output of
light and sound makes this system more effective than traditional alarm clocks, offering a customizable and comfortable waking experience.
By incorporating these outputs, the project achieves its goal of providing a more humane, stress-free, and enjoyable way of waking up. Future improvements could involve adding features like volume control, custom FM tuning, and additional sensory outputs to enhance the overall user experience further.
 
Conclusion : 
The FM Radio Alarm Clock with RGB Sunrise Effect successfully combines modern embedded systems with the principles of natural light therapy and auditory stimulation to create an innovative and effective wake-up solution. By integrating an RTC module, FM radio module, and RGB LEDs, the system offers a seamless and customizable user experience. The gradual sunrise effect provided by the RGB LEDs helps simulate natural waking conditions,
making the transition from sleep to wakefulness smoother and more pleasant. Additionally, the FM radio alarm introduces an enjoyable auditory experience by playing a preferred FM station, ensuring a stress-free start to the day.
Throughout the development process, the system demonstrated its ability to accurately track time, produce a gradual light increase, and provide reliable FM radio output. The
combination of these elements presents a significant improvement over traditional alarm clocks, offering a more humane and holistic approach to waking up.
In conclusion, this project showcases the potential of embedded systems in creating smart, user-friendly devices that enhance daily living. Future enhancements such as customizable FM station tuning, volume control, Bluetooth connectivity, and even IoT integration could further improve the system’s functionality, making it a versatile and scalable solution for
users seeking a more natural and enjoyable way to wake up.
 
References : 
•	Avery, D. H., Lack, L., Schoerning, A., & Thapan, K. (2007). Dawn simulation and wake-up times in seasonal affective disorder. Journal of Affective Disorders, 98(1-2), 177-181.
•	Gabel, V., Maire, M., Follenius, M., & Brandenberger, G. (2002). Light exposure before sleep improves sleep quality and morning alertness in simulated shift work. Journal of Sleep Research, 11(2), 145-152.
•	Wirz-Justice, A., Benedetti, F., Berger, M., Fietze, I., Joseph, D. H., Kim, L., ... & Terman, M. (2005). Chronotherapeutics (light and wake therapy) in affective disorders. Dialogues in Clinical Neuroscience, 7(4), 381-391.
•	TEA5767 FM Radio Module Datasheet. NXP Semiconductors.
•	DS3231 Real-Time Clock Module Datasheet. Maxim Integrated.
•	WS2812B Addressable LED Datasheet. Worldsemi.
•	Arduino Uno Official Website. (n.d.). Retrieved from Arduino.cc
•	Sony ICF-C1 FM/AM Clock Radio User Manual. Sony Corporation.
•	JBL Horizon FM Radio Alarm Clock User Manual. JBL by Harman.
•	Philips Wake-Up Light Product Information. Philips Consumer Lifestyle.
•	Lumie Bodyclock Product Information. Lumie.
•	Journal of Clinical Sleep Medicine. (Various Articles on Light Therapy). American Academy of Sleep Medicine.
