# M5Racing
## M5Stack DAS Racing description:

M5Racing (M5R) is a new Data Acquisition System (DAS) for moving vehicles (cars, motorcycles, bikes,...), providing data sampling, revision (over a very schematic GUI of 2" 320x240 integrated screen) and logging (when needed).

This new Racing Data Logger is based on the M5Stack modular system. M5Stack Core Base development board is highly efficient, covering with industrial grade case an ESP32, 16MB of flash memory and Bluetooth communication.

The mean advantage is the powerfull modular system that provides de M5Stack design, so you can get only the modules and sensors you need to achieved you goals. For example, if you only need TTPMS and some OBDII ECU data, there is no need to mount any module as the bluetooth conectivity is ready to use on the base M5Stack Core.

 - Data Acquisition System (DAS) and Analysis for racecar and motorcycle racing
 - Telemetry and data logging for all sensors installed and ECU vehicle data
 - 2.0-inch, 320x240 Colorful TFT LCD, with a maximun brightness of 853 nit
 - GUI for navigating through data and config menus
 - ESP32 (2 low-power Xtensa® 32-bit LX6 microprocessors at 240MHz, dual core, 600 DMIPS)
 - Bluetooth dual (classic BT 3.0 and BLE 4.0) over 2.4 GHz 3D Antenna
 - FreeRTOS firmware and 16MB of flash memory  
 - On-track engineering with LIVE sensors reading
 - Easy FIRMWARE upgrade via new "firmware.bin" realeases
 - Based on M5Stack Core:
   - Option 1: https://docs.m5stack.com/en/core/basic_v2.6 (cheapest option)
   - Option 2: https://docs.m5stack.com/en/core/gray (another valid option)

At the end, we show the list of which modules, sensors units and special installation process, needed for the multiple functionalities of M5R.

## M5R Full Technical Data Specs: 

 - 1 - 16GB microSD CARD STORAGE
 
   - Up to 16GB FAT32 formated microSD TF cards
   - Creates compatible UTF-8 .CSV format files
   - Can be opened with:
     - RaceRender 3.0 Data Analisis and Data-Overlay video (FREEWARE)
     - https://serious-racing.com
     - RaceChrono
     - TimeAttack
     - TrackAddict
     - DashWare
     - MS Excel Data Sheets or similar
       
 - 2 - 10 Hz GPS DATA
 
   - 10 times a second GPS data for:
     - automatic lap timer
     - automatic on-track recognition (plus than 1000 tracks available)
     - accurate track lines path for every curve
     - accurate time and date
     - altitude data and moving speed
         
 - 3 - 50 Hz DATA LOGGING
 
   - 50 times a second (every 20 ms) logging
   - High-speed data sampling for high variable data sensors such as:
     - Suspension
     - G-forces
     - IR temps (tires and brakes) 
 
 - 4 - OBD II ECU DATA
 
   - Classic Bluetooth 3.0 connection
   - Needs an OBDII to BT 3.0 dongle with compatible ELM327 chipset (Version 1.5 or higher) and 2.1 software
   - Also BT 2.0 and BT 4.0: compatibility depends of the vehicle and OBDII to BT dongle used
   - ECU Engine RPM
   - SHIFT-light indicator
   - ECU SPEED data
   - Actual GEAR
   - ECU Throttle position sensor data (TPS)
   - On-screen alerts for too high Coolant temperature
 
 - 5 - TTPMS DATA
 
   - Inside tire temperature and pression monitoring system
   - BLE Bluetooth 4.0 connection with open data TTPMS sensors
   - Includes on-screen alerts for too low or too high tire pressure
   - Includes easy "check-by-Colour" optimum or out-of-range values
   - 2 options:
     - Internal (real TTPMS but needs installation):
       - https://amzn.eu/d/5TqwCvm
       - https://amzn.eu/d/ep8Rzsu
       - https://amzn.eu/d/hr0sHYG
     - External (very easy install but temperature is ambient temp):
       - https://amzn.eu/d/6uYdyAY
       - https://amzn.eu/d/dzelCKM

 
 - 6 - TIRE TEMPERATURES
 
   - 3-zone or 8-zone expanded data sampling to choose from
   - Based on external infrared (IR) sensors (from -40 to 380ºC)
   - Includes "check-by-colour" values and alerts for too low or too high temperature
   - On-screen data analysis simplified:
     - Outside, middle and inside temps for each car tire
       - At setup, includes camber tips for optimum performance
     - Left, centre and right temps for each motorcycle (bike) tire
 
 - 7 - ENVIROMENTAL DATA
 
   - Ambient light (Lux)
   - Ambient temperature (ºC)
   - Ambient pressure (BAR)
   - Ambient humidity (%)
   - Includes alerts for too low or too high ambient temp:
     - Below 7ºC
     - Above 32ºC
 
 - 8 - G-SENSORS and 9-axis IMU
 
   - Longitudinal acceleration:
     - Under braking (negative G-values)
     - Throttling (positive G-values)
   - Includes PITCH angle for live rake sampling 
   - Lateral turning forces
   - LEAN angle (specially usefull for motorcycle (bike))
   - YAW or rotation angle to detect under/over steering of the vehicle
 
 - 9 - ROTOR and CALIPER TEMPERATURE
 
   - Based on external infrared (IR) sensors
   - Includes alerts for too low or too high rotor values
     - Below 100ºC (cold)
     - Above 600ºC (overheated)
   - Includes alerts for too high caliper values
     - Above 200ºC (overheated / risk of vaporisation)
 
 - 10 - STEERING ANGLE
 
 - 11 - THROTTLE POSITION SENSOR
 
   - Only if not OBD II BT in use:
     - Car: must install a ToF sensor under de throttle lever
     - Motorcycle: must install an angle sensor inside de throttle
 
 - 12 - SUSPENSION TRAVEL AND SAG ADJUSTMENT
 
   - Measures the suspension travel for each wheel
   - Includes SAG easy process adjustment:
     - 3-step guide with description and images
     - With "check-by-colour" optimum calculated values 
     - Also includes lIVE SAG for on-track setup 
   - Includes alerts for:
     - Near bottoming alert: too much diving of the front under braking
     - Too poor SAG
 
 - 13 - AUTO POWER SHIFTER (APS)
 
   - Only for models equiped with UP/DOWN shifter (UP-Shifter and Blipper)
   - Mandatory OBD II BT active
   - Totally tunable with 4 riding modes:
     - ECO, STREET, SPORT and TRACK
     - Each mode totally configurable for UP RPM, DOWN RPM, for each gear!!!
 
 - 14 - BRAKE PRESSURE SENSORS
 
   - Brake sensor with 2 options and functionality:
     - ON/OFF: only senses if you brake or not via brake light activation
     - Proper pressure gauge/s: samples exact pressure at each brake lever (needs installation and bleeding of new brake line hoses)
 
 - 15 - 5" HMI REALTIME DASHBOARD

   - 5" Full-HD touchscreen monitor with:
     - Better GUI design than the M5Stack core itself, with multiple graphical screens
     - Professional RPM LED strip with SHIFT-light indicator (flashes white) totally syncronized with APS
     - Show all the LIVE data of the vehicle
     - Manage information
     - Navigate through configuration menus
     - Shows alarms and alerts:
       - GPS signal alert
       - TTPMS alarm
       - Coolant alarm
       - Ambient temperature alert


## Needed Modules, sensors and special installation (related with functionality)

 - 1 - 16GB microSD CARD STORAGE -> No special module needed (M5Stack Core included functionality)
 - 2 - 10 Hz GPS DATA
 - 3 - 50 Hz DATA LOGGING -> No special module needed (M5Stack Core included functionality)
 - 4 - OBD II ECU DATA -> No special module needed (M5Stack Core included functionality) 
 - 5 - TTPMS DATA -> No special module needed (M5Stack Core included functionality)
 - 6 - IR TIRE TEMPERATURES
 - 7 - ENVIROMENTAL DATA -> No special module needed (M5Stack Core included functionality)
 - 8 - G-SENSORS and 9-axis IMU
 - 9 - IR BRAKES TEMPERATURE
 - 10 - STEERING ANGLE -> No special module needed (M5Stack Core included functionality)
 - 11 - THROTTLE POSITION SENSOR -> No special module needed (M5Stack Core included functionality) 
 - 12 - SUSPENSION TRAVEL AND SAG ADJUSTMENT
 - 13 - AUTO POWER SHIFTER (APS)
 - 14 - BRAKE PRESSURE SENSOR -> No special module needed (M5Stack Core included functionality)
 - 15 - 5" HMI REALTIME DASHBOARD
