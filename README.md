

# 🗑️ Smart Dustbin


## 📌 Project Overview

The **Smart Dustbin** is an Arduino-based automated waste disposal system that opens its lid automatically when it detects a nearby object using an ultrasonic sensor. This touchless mechanism improves hygiene and promotes cleanliness by reducing physical contact.

The project demonstrates the practical use of **sensors and actuators** in automation and smart systems.

----------

## 📝 Project Description

This project is designed to create a **touch-free automatic dustbin** using an ultrasonic sensor and a servo motor. When a user brings their hand close to the dustbin, the ultrasonic sensor detects the distance. If the distance is below a predefined threshold, the Arduino triggers the servo motor to open the lid. After a short delay, the lid closes automatically.

The system is simple, cost-effective, and suitable for smart city and hygiene-related applications.

----------

## 🧰 Components Used

-   Arduino Uno
    
-   Ultrasonic Sensor (HC-SR04)
    
-   Servo Motor
    
-   Breadboard
    
-   Jumper Wires
    
-   Power Supply (USB / Battery)
    

----------

## 💻 Software and Tools Used

-   Arduino IDE
    
-   Embedded C / Arduino Programming Language
    
-   USB Cable
    

----------

## ⚙️ Working Principle

1.  The ultrasonic sensor continuously emits ultrasonic waves.
    
2.  These waves reflect back when an object (hand) is placed near the dustbin.
    
3.  The Arduino calculates the distance using the echo time.
    
4.  If the distance is less than the set threshold:
    
    -   The servo motor rotates to open the lid.
        
5.  After a short delay:
    
    -   The servo motor returns to its original position, closing the lid.
        

----------

## 🧠 Algorithm

1.  Start the system
    
2.  Initialize ultrasonic sensor and servo motor
    
3.  Trigger ultrasonic sensor
    
4.  Measure echo pulse duration
    
5.  Calculate distance
    
6.  If distance < threshold:
    
    -   Open dustbin lid
        
    -   Wait for a short delay
        
    -   Close dustbin lid
        
7.  Repeat continuously
    

----------

## ▶️ How to Run the Project

1.  Connect all components according to the circuit diagram
    
2.  Connect Arduino Uno to the computer using a USB cable
    
3.  Open Arduino IDE
    
4.  Select **Arduino Uno** as the board and choose the correct COM port
    
5.  Upload the code to the Arduino
    
6.  Power the system
    
7.  Bring your hand near the sensor to observe automatic lid operation
    

----------

## 🎯 Expected Outcomes

-   Automatic opening and closing of dustbin lid
    
-   Accurate object detection using ultrasonic sensor
    
-   Smooth servo motor operation
    
-   Touch-free and hygienic waste disposal
    

----------

## 🏫 Applications

-   Smart homes
    
-   Smart cities
    
-   Public places (malls, offices, hospitals)
    
-   Hygiene management systems
    
-   Educational robotics projects
    

----------

## ✅ Advantages

-   Touchless operation
    
-   Improves hygiene
    
-   Low-cost and energy efficient
    
-   Easy to build and maintain
    
-   Suitable for beginners in Arduino and robotics
    

----------

## 🚀 Future Improvements

-   Add LCD display for status messages
    
-   Include buzzer or LED indicators
    
-   Add Bluetooth or IoT-based monitoring
    
-   Solar-powered operation
    
-   Waste level detection system
    

--------