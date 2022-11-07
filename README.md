# M5Racing
## M5Stack DAS Racing description:

M5Racing (M5R) is a new Data Acquisition System (DAS) for any type of vehicle (cars, motorcycles, bikes, etc.). It provides data sampling, revision (on a small integrated GUI screen or an optional, 5" external display) and logging (when needed).

This new Racing Data Logger is based on the M5Stack modular system. The M5Stack Core Base development board is highly efficient and includes an industrial grade case, an ESP32 with 16MB of flash memory and Bluetooth communication.

The main advantage is the powerful modular system provided by the M5Stack design, which means you only have to get the modules and sensors you need for achieving your objectives. For example, if you only need TTPMS and some OBD-II ECU data, no modules have to be installed, given that Bluetooth connectivity is ready to use in the base M5Stack Core.

- Data Acquisition System (DAS) and Analysis for car and motorcycle racing.
- Telemetry and data logging for all installed sensors and vehicle ECU data.
- 2.0-inch, 320x240 Colour TFT LCD, with a maximum brightness of 853 nit.
- GUI for browsing through data and config menus.
- ESP32 (two low-power Xtensa® 32-bit LX6 microprocessors at 240 MHZ, dual core, 600 DMIPS).
- Dual Bluetooth (classic BT 3.0 and BLE 4.0) with 2.4-GHz 3D Antenna.
- FreeRTOS firmware and 16MB of flash memory.
- On-track engineering, with LIVE sensor reading.
- Easy FIRMWARE upgrade through new "firmware.bin" releases.
- Based on the M5Stack Core: 
  - Option 1: https://docs.m5stack.com/en/core/basic_v2.6 (most economical option).
  - Option 2: https://docs.m5stack.com/en/core/gray (another valid option).
- The log files that are created can be opened with: 
  - RaceRender 3.0 by HP Tuners, which creates a Data-Overlay video (WIN and MAC / freeware).
  - https://serious-racing.com (cloud only / freeware).
  - RaceChrono Pro data analysis with sync video (Android / iOs, 23 euros per license).
  - Circuit Tools by RaceLogic VBOX and data analysis with sync video (WIN and MAC / freeware).
  - DashWare by GoPro, which creates a Data-Overlay video (WIN / freeware).
  - Race Studio 3 by AIM (WIN / freeware).
  - MS Excel or similar data spreadsheets or txt (WIN and MAC / freeware).

A list of the modules, sensor units and special installation processes that are needed for the multiple functionalities of M5R is shown below.


## M5R Full Technical Data Specs: 

- 16 GB microSD CARD STORAGE
  - Up to 16GB FAT32 formatted microSD TF cards
  - Creates compatible UTF-8 .CSV format files
  - Compatibility with almost any data analysis program
  - Unlimited session length, ideal for 24-hour races

- 10 Hz GPS DATA
  - GPS data 10 times per second for: 
    - automatic lap timer
    - automatic on-track recognition (more than 1000 tracks available)
    - accurate track paths for every curve
    - accurate time and date
    - altitude and speed data

- 50 Hz DATA LOGGING
  - Logging 50 times per second (every 20 ms) 
  - High-speed data sampling for high variable data sensors such as: 
    - Suspension
    - G-forces
    - IR temps (tires and brakes)

- OBD-II ECU DATA
  - Classic Bluetooth 3.0 connection
  - Requires an OBD-II-to-BT 3.0 dongle with a compatible ELM327 chipset (Version 1.5 or higher) and 2.1 software
  - Also BT 2.0 and BT 4.0: compatibility depends on the vehicle and the OBD-II-to-BT dongle used
  - ECU Engine RPM
  - SHIFT-light indicator
  - ECU SPEED data
  - Actual GEAR
  - ECU throttle position sensor data (TPS)
  - Coolant temp (with alert if temp > 106º C)
  - On-screen alerts for coolant temperature too high
- TTPMS DATA
  - Inside tire temperature and pressure monitoring system
  - BLE Bluetooth 4.0 connection with open data TTPMS sensors
  - Up to 1 sample per second (1 Hz) if sensor data changes rapidly
  - Includes on-screen alerts for tire pressure that is too low (20 PSI) or too high
  - Includes easy "check-by-colour" for optimum or out-of-range values
  - 2 options: 
    - Internal (real TTPMS, but requires installation): 
      - https://amzn.eu/d/5TqwCvm
      - https://amzn.eu/d/ecVz5fE
    - External (very easy install, but temperature is ambient temp): 
      - https://amzn.eu/d/6uYdyAY
      - https://amzn.eu/d/dzelCKM
      - https://amzn.eu/d/eoFtA7H
- TIRE TEMPERATURES
  - 3-zone or 8-zone expanded data sampling to choose from
  - Based on external infrared (IR) sensors (from -40º to 380º C)
  - Includes "check-by-colour" values and alerts for temperature too low or too high (> 100º C)
  - Simplified on-screen data analysis: 
    - Outside, middle and inside temps for each car tire 
    - At setup, includes camber tips for optimum performance
    - Left, centre and right temps for each motorcycle (bike) tire
- ENVIRONMENTAL DATA
  - Ambient light (Lux)
  - Ambient temperature (º C)
  - Ambient pressure (BAR)
  - Ambient humidity (%)
  - Includes alerts for ambient temp too low or too high: 
    - Below 5º C
    - Above 32º C
- G-SENSORS and 9-axis IMU
  - LEAN angle (especially useful for motorcycle riders and bikers)
  - YAW or rotation angle to detect under/over steering of a vehicle
  - Includes PITCH angle for live rake sampling
  - Longitudinal acceleration: 
    - Under braking (negative G-values)
    - Throttling (positive G-values)
  - Lateral acceleration: 
    - Cornering forces
- ROTOR and CALIPER TEMPERATURE
  - Based on external infrared (IR) sensors
  - Includes alerts for rotor values that are too low or too high
    - Below 100º C (cold)
    - Above 600º C (overheated)
  - Includes alerts for too-high caliper values 
    - Above 180º C (overheated / risk of vaporisation)
- STEERING ANGLE
- THROTTLE POSITION SENSOR
  - Only needed if OBD-II BT is not in use: 
    - Car: a ToF sensor must be installed under the throttle lever
    - Motorcycle: an angle sensor must be installed inside the throttle
- SUSPENSION TRAVEL AND SAG ADJUSTMENT
  - Measures the suspension travel for each wheel
  - Includes easy SAG adjustment process: 
    - 3-step guide with description and images
    - With "check-by-colour" for optimum calculated values
    - Also includes LIVE SAG for on-track setup
  - Includes alerts for: 
    - Near-bottoming alert (if less than 10 mm of travel left): the front dives too much while braking
    - Poor SAG
- AUTO POWER SHIFTER (APS)
  - Only for models equipped with UP/DOWN shifter (UP-Shifter and Blipper)
  - Requires an active OBD-II-to-BT 3.0 or 4.0 dongle 
  - Completely tuneable with 4 riding modes: 
    - ECO, STREET, SPORT and TRACK
    - Each mode completely configurable for UP RPM and DOWN RPM, for each gear!!!
    - Not only FULL AUTO but also a FULL MANUAL UP/DOWN gear selector in any mode
  - For more convenient MODE selection and AUTO/MANUAL APS UP/DOWN gear selection, one of these 5-button controls is needed: 
    - https://amzn.eu/d/10rhYnT
    - https://amzn.eu/d/iwBvQux
- BRAKE PRESSURE SENSOR(S)
  - Brake sensor with 2 options and functionalities: 
    - ON/OFF: only senses if you do or don’t brake via brake light activation
    - Proper pressure gauge(s): samples exact pressure at each brake lever (requires installation and bleeding of new brake line hoses)
- 5" HMI REALTIME DASHBOARD
  - 5-inch 800x480 touchscreen monitor with: 
    - Racing Dashboard design
    - A 20-LED strip that shows the actual RPM with colour ramping
    - SHIFT-light indicator (all LEDs flash in bright white), completely synchronised with the APS
    - Shows all of the vehicle’s LIVE data and sensors
    - GUI design better than the M5Stack Core alone, with multiple graphic screens
    - Information management
    - Browsing through the configuration menus
    - Adaptative brightness to actual ambient light (lux)
    - Shows alarms and alerts: 
      - GPS signal alert
      - TTPMS alarm
      - Coolant alarm
      - Ambient temperature alert
      - TTPMS out of range alerts


## Needed Modules, sensors and special installation (related with functionality)

 - 16GB microSD CARD STORAGE -> No special module needed (M5Stack Core included functionality)
 - 10 Hz GPS DATA
 - 50 Hz DATA LOGGING -> No special module needed (M5Stack Core included functionality)
 - OBD II ECU DATA -> No special module needed (M5Stack Core included functionality) 
 - TTPMS DATA -> No special module needed (M5Stack Core included functionality)
 - IR TIRE TEMPERATURES
 - ENVIRONMENTAL DATA -> No special module needed (M5Stack Core included functionality)
 - G-SENSORS and 9-axis IMU
 - ROTOR and CALIPER TEMPERATURE
 - STEERING ANGLE -> No special module needed (M5Stack Core included functionality)
 - THROTTLE POSITION SENSOR -> No special module needed (M5Stack Core included functionality) 
 - SUSPENSION TRAVEL AND SAG ADJUSTMENT
 - AUTO POWER SHIFTER (APS)
 - BRAKE PRESSURE SENSOR -> No special module needed (M5Stack Core included functionality)
 - 5" HMI REALTIME DASHBOARD
