# HE3D Firmware for EI3

# Marlin-1.1.0RC8 - He3d - single extruder - large bed - Runout Sensor

  - Configuration_adv.h
  
		uncomment #define FILAMENT_CHANGE_FEATURE

  - Configuration.h

		#define MOTHERBOARD 55
		#define CUSTOM_MACHINE_NAME "HE3D i3 Large"
		#define X_MAX_POS 200
		#define Y_MAX_POS 300
		#define Z_MAX_POS 220
		uncomment #define FILAMENT_RUNOUT_SENSOR
		#define FIL_RUNOUT_INVERTING true

  - pins_RAMPS.h
  
		revert #define SERVO0_PIN       11
		#define FIL_RUNOUT_PIN      12
		
  - pins_MKS_15.h
  
		#undef FIL_RUNOUT_PIN
		#define FIL_RUNOUT_PIN     12
		
# Where to connect the sensor?
You need to put your endstop on pin D11 is the third pin after the z min endstop

see this for help

![alt tag](https://github.com/Elenedeath/HE3D-Firmware/blob/Runout-Sensor/D12%20pins.jpg)
