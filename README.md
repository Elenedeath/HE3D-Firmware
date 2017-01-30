# HE3D Firmware for EI3

# Ultimaker2Marlin - Master Branch
  - Latest Commits
  
		Commits on Jan 12, 2017
		Merge pull request #122 from Ultimaker/EM-1311_build_plate_can_raise 68a1ade

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