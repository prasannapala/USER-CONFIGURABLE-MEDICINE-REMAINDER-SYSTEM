💊 User-Configurable Medicine Reminder System using LPC2148 (ARM7)

⭐ Overview A User-Configurable Medicine Reminder System developed using the LPC2148 ARM7 Microcontroller to help users take medicines on time. The system allows users to configure medicine schedules through a 4×4 Matrix Keypad while the Real-Time Clock (RTC) continuously monitors the current date and time. Whenever a configured medicine time is reached, the system automatically alerts the user using a buzzer and displays a reminder message on the 16×2 LCD.

The system performs the following operations:

⏰ Real-Time Clock Monitoring

⌨️ Medicine Time Configuration

💾 Medicine Schedule Storage

📟 Real-Time LCD Display

🔔 Automatic Medicine Reminder

✅ User Acknowledgement

The LPC2148 continuously compares the RTC time with the stored medicine schedules. When the scheduled time matches, the buzzer generates an alert and the LCD displays "Take Medicine Now". The reminder stops when the user acknowledges it using Switch-2 or automatically after the timeout period.

------------------------------------------------------------------------------------------------------------------------------
