# M5Racing
## M5Stack DAS Racing description:

M5Racing (M5R) is a new Data Acquisition System (DAS) for any type of vehicle (cars, motorcycles, bikes, etc.). It provides data sampling, revision (on a small integrated GUI screen or an optional, 5" external display) and logging (when needed).

This new Racing Data Logger is based on the M5Stack modular system. The M5Stack Core Base development board is highly efficient and includes an industrial grade case, an ESP32 with 16MB of flash memory and Bluetooth communication.

The main advantage is the powerful modular system provided by the M5Stack design, which means you only have to get the modules and sensors you need for achieving your objectives. For example, if you only need TTPMS and some OBD-II ECU data, no modules have to be installed, given that Bluetooth connectivity is ready to use in the base M5Stack Core.

  • Data Acquisition System (DAS) and Analysis for car and motorcycle racing.
  • Telemetry and data logging for all installed sensors and vehicle ECU data.
  • 2.0-inch, 320x240 Colour TFT LCD, with a maximum brightness of 853 nit.
  • GUI for browsing through data and config menus.
  • ESP32 (two low-power Xtensa® 32-bit LX6 microprocessors at 240 MHZ, dual core, 600 DMIPS).
  • Dual Bluetooth (classic BT 3.0 and BLE 4.0) with 2.4-GHz 3D Antenna.
  • FreeRTOS firmware and 16MB of flash memory.
  • On-track engineering, with LIVE sensor reading.
  • Easy FIRMWARE upgrade through new "firmware.bin" releases.
  • Based on the M5Stack Core: 
      ◦ Option 1: https://docs.m5stack.com/en/core/basic_v2.6 (most economical option).
      ◦ Option 2: https://docs.m5stack.com/en/core/gray (another valid option).
  • The log files that are created can be opened with: 
      ◦ RaceRender 3.0 by HP Tuners, which creates a Data-Overlay video (WIN and MAC / freeware).
      ◦ https://serious-racing.com (cloud only / freeware).
      ◦ RaceChrono Pro data analysis with sync video (Android / iOs, 23 euros per license).
      ◦ Circuit Tools by RaceLogic VBOX and data analysis with sync video (WIN and MAC / freeware).
      ◦ DashWare by GoPro, which creates a Data-Overlay video (WIN / freeware).
      ◦ Race Studio 3 by AIM (WIN / freeware).
      ◦ MS Excel or similar data spreadsheets or txt (WIN and MAC / freeware).

A list of the modules, sensor units and special installation processes that are needed for the multiple functionalities of M5R is shown below.

## M5R Full Technical Data Specs: 

    • 16 GB microSD CARD STORAGE
        ◦ Up to 16GB FAT32 formatted microSD TF cards
        ◦ Creates compatible UTF-8 .CSV format files
        ◦ Compatibility with almost any data analysis program
        ◦ Unlimited session length, ideal for 24-hour races

    • 10 Hz GPS DATA
        ◦ GPS data 10 times per second for: 
            ▪ automatic lap timer
            ▪ automatic on-track recognition (more than 1000 tracks available)
            ▪ accurate track paths for every curve
            ▪ accurate time and date
            ▪ altitude and speed data

    • 50 Hz DATA LOGGING
        ◦ Logging 50 times per second (every 20 ms) 
        ◦ High-speed data sampling for high variable data sensors such as: 
            ▪ Suspension
            ▪ G-forces
            ▪ IR temps (tires and brakes)
    
    

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
