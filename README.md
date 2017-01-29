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
  
		#define SERVO0_PIN       -1
		#define FIL_RUNOUT_PIN      11
		
  - pins_MKS_15.h
  
		#undef FIL_RUNOUT_PIN
		#define FIL_RUNOUT_PIN     11