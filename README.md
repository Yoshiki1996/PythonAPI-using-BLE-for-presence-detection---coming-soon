# BLE SCANNER AND DATA GENERATOR USING RASPBERRY PI3

Code is run on Python V2.x and Raspberry Pi3 Bluetoothctl environment

To run any of the code, type: "sudo python CODENAME.py" in terminal

1. BLE_SCANNER: Scans all available BLE devices within the proximity. Python fetches
   Raspberry Pi Bluetoothctl environment.
   
2. BLE_TABLE: Generates a table for each BLE device. 

3. BLE_DATA: Compiles all the BLE code above into one (calling this file will execute all functions above automatically).
   Stores the present date, time and mac and presence string upon scan real-time. It dynamically retrieves the BLE device every call,
   hence detects whether a new BLE device is present, or if a pre-existing device disappears.
   
Note: From experiment it seems the maximum presence detection is within 15-20 [meters]. Enough to detect
      any BLE device in a single room.
   
   
   
