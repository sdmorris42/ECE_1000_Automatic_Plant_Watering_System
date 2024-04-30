# ECE_1000_Automatic_Plant_Watering_System
# Project Members
Summer Morris- Electrical Engineering Major 

Isaiah Short- Electrical Engineering Major
# Project Summary
It can be difficult to give plants the right amount of water necessary to grow. With an automatic plant watering system, plants will not only be able to receive the perfect amount of water, but the system will also decrease the amount of wasted water. This project is significant because it is motivated behind the environmental challenge in IEEE. With a more precise watering system, plants will be able to flourish while not wasting water. It is crucial to implement systems similar to this project, especially in locations where water is more difficult to obtain. 
# Project Accomplishments
The automatic plant watering system continually monitors the moisture level and updates the percentage every second. The moisture level, as long as the water pump has sufficient water and power is supplied, will continually stay within the range of approximately 29 percent to 41 percent, when given a minimum moisture level of 30 percent and maximum level of 40 percent. When the moisture level is equal to or below 30 percent, the pump will turn on, the RGB LED will turn red, and the OLED will display the text, "Pump On." When the moisture level is at least 40 percent, the pump will turn off, the RGB LED will turn green, and the OLED will display the text, "Pump Off." While the moisture percentage is between 30 and 40 percent, the pump will remain on or off. When the user presses button 1 on the Raspberry Pi Pico, the pump will turn on, the RGB LED will turn blue, and the OLED will display the text, "Manual Mode." The moisture percentage updates on the system and OLED every second. 
