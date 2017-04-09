# HE3D Firmware for EI3

# Ultimaker2Marlin - Master Branch
  - Latest Commits
  
		Commits on Mar 20, 2017
		Merge branch 'EM-1392_fix_53_day_temperature_error'

  - Configuration_adv.h
  
		uncomment #define FILAMENTCHANGEENABLE
	
  - Configuration.h
  
		#define BAUDRATE 115200
		#define MOTHERBOARD 55
		#define CUSTOM_MACHINE_NAME "HE3D UM2"
		#define X_MAX_POS 200
		#define Y_MAX_POS 300
		#define Z_MAX_POS 220

  - pins.h
  
		added custom motherboard 55 and define pin