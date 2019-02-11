# NilanModbus

@ All the credits for the code work on this goes to original designer Dan Gunvald.

I have tried to make an attempt to make it work with Home Assistant instead of OpenHab, which it is originally designed for.

When the setup of the ESP8266 and MODBUS interface is done, it is time for using it in Home Assistant together with MQTT.

MQTT Topics:

ventilation/RunSet          (ON uses payload 1) (Switch for turning the Nilan ON)
ventilation/RunSet          (OFF uses payload 0) (Switch for turning the Nilan OFF) 

ventilation/control/RunSet

ventilation/ModeSet         (Changes the different modes like - Auto, Heat, Cool)

ventilation/control/ModeSet (The state topic for the modes)

ventilation/VentSet         (Sets the ventilation speed)

ventilation/control/VentSet (The state topic for ventilation speed)

ventilation/TempSet         (Set the temperature)

ventilation/control/TempSet (The state topic for temperature)

temp/T7_Inlet               (Shows the inlet temperature from the sensor on the Nilan)

temp/T8_Outdoor             (Shows outdoor temp from the sensor on the Nilan)



               
