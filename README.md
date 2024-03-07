Implemented an IoT Based Bicycle using ESP-32 and programmed it using Ardiuno IDE, HTML was used to make the webpages and the following webpages were hosted on a local WiFi network for users to use, The following sensors were implemented:
-MPU 6050(Gyroscope)
-NEO 6M(GPS)
-Servo Motor(SG 90)
-Hall Sensor(KY 024)

The gyroscope is used to determine the orientation of the cycle. The gps is used to find the location. The hall sensor is used to find the distace, the hall sensor counts each rotation of the wheel and calculates the distance accordingly. The servo motor is used for the locking mechanism for the cycle.
All these components are connected to the ESP-32 which is the main microcontroller and also hosts the webpage on local server.
