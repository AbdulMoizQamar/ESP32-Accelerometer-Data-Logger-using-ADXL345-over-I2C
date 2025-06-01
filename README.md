# ESP32-Accelerometer-Data-Logger-using-ADXL345-over-I2C
This Arduino sketch reads real-time acceleration data (X, Y, Z axes) from the ADXL345 accelerometer connected via I2C (SDA: GPIO 8, SCL: GPIO 9) to an ESP32 board.

📝 Description:
This Arduino sketch reads real-time acceleration data (X, Y, Z axes) from the ADXL345 accelerometer connected via I2C (SDA: GPIO 8, SCL: GPIO 9) to an ESP32 board.

The program:
Initializes the ADXL345 using the Adafruit Sensor library
Configures the range to ±16g
Displays sensor info, range, and data rate
Continuously reads and prints acceleration in m/s² over the Serial Monitor

✅ Features:
I2C communication with ADXL345
Uses Adafruit_ADXL345_U and Adafruit_Sensor libraries
Displays sensor characteristics (range, resolution, etc.)
Continuously prints real-time X, Y, Z acceleration
Adjustable range and data rate settings

📦 Requirements:
ESP32 development board
ADXL345 accelerometer
Arduino IDE with ESP32 board support

Libraries:
Adafruit ADXL345 Unified
Adafruit Unified Sensor

🔌 Wiring (I2C mode):
ADXL345 Pin	ESP32 Pin
SDA	GPIO 8
SCL	GPIO 9
VCC	3.3V
GND	GND

