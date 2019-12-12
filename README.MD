Ender4_MKS_Gen_L_8bits
Configuração completa para a Adaptação da MKS Gen L na Ender4 com Display original

#define BAUDRATE 115200
#define MOTHERBOARD BOARD_MKS_GEN_L

#define BED_MAXTEMP 150

#define HEATER_0_MAXTEMP 280

//Motor Drivers Definition
#define X_DRIVER_TYPE LV8729
#define Y_DRIVER_TYPE LV8729
#define Z_DRIVER_TYPE LV8729
#define E0_DRIVER_TYPE DRV8825

// The size of the print bed
#define X_BED_SIZE 220
#define Y_BED_SIZE 220

//Leveling BED
#define PROBE_MANUALLY
#define MESH_BED_LEVELING

// Preheat Constants
#define PREHEAT_1_LABEL "PETG"
#define PREHEAT_1_TEMP_HOTEND 240
#define PREHEAT_1_TEMP_BED 60
#define PREHEAT_1_FAN_SPEED 0

#define PREHEAT_2_LABEL "ABS"
#define PREHEAT_2_TEMP_HOTEND 230
#define PREHEAT_2_TEMP_BED 115
#define PREHEAT_2_FAN_SPEED 0

//Language Config
#define LCD_LANGUAGE pt_br

//Display Config
#define REPRAP_DISCOUNT_SMART_CONTROLLER