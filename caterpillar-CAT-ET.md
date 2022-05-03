# CAT ET caterpillar ECM programming Guide

#### Sections
1. Gather Engine Info
2. Select correct ECM partnumber
3. Select correct flash file number
4. Create work orders


## Section 1 Gather Engine Info

**Gather Information from**
  - ECM order form (yellow slip)
  - work orders of original
    - if original ECM was communicating when received a
       workorder will exist using filename format customerName(INITIAL/FINAL) MM-D-YY
       ex: Texas Diesel (INTIAL) 1-21-22.pdf
    - ecm replacement file will also exist with same format but with .xls file type
       ex: Texas Diesel (INTIAL) 1-21-22.xls   

**Required Information if no work orders** see below for details
1. Engine serial number
2. Vin Number
3. Horsepower and Torque desired
4. Vehicle speed limit desired
5. Engine brakes installed on vehicle?
6. A/C pressure Switch


##### Required info Detailed
1. Engine Serial Number
   - ex: 6NZ12345 will always be a 3 digit alpha numeric (6NZ) folowed by 5 numbers (12345)
2. VIN number to verify if on a GM chasis
3. Horse Power
    - if none specified you may choose any available for engine serial number or if you nice max rating
4. Vehicle speed limit
    - some customers will say kilometers per hour
      if they specify anything over 100 they most likely mean KPH especially from canada
      most units will not accept over 100 MPH verify with customer
5. Enginge Brakes installed ?
    - Also known as Jake Brakes
    - Depending on application and terrain
    some settings for engine brakes will be more desirable especially in mountainous terrain
6. Air conditioning pressure switch controls fan ?
    -some A/C systems require engine radiator fan to activate in order to regulate pump pressure for A/C
     if not set up correctly fan will stay on all the time or A/C will not function for extended periods



## Section 2 Select Correct ECM Partnumber
  - Board type
    - KM KA
      - Compatible with
      - 6NZ
      - 7CZ
      - 2WS
      - 2KS ... others to be added
    - IK
      - Compatible with
      - MBN
      - MBL
    - IE
      - Compatible with
      - KAL
      - WAX
    - JJ
      - Compatible with
      - BXS
      - KCB
    - KC
      - Compatible with
      - 8YL
      - 7AS
      -
    - FV FW
      - Compatible with
      - 7AS only
        - FV for non GM chasis
        - FW **ONLY** for GM Chasis
    - IC
      - Compatible with
    - IH
      - Compatible with
## Sectino 3 Select correct flash file number
  - Open flash-file-list.pdf on desktop
  - using engine serial first 3 digits ex: 6nz from **6nz**12345 press control + f
    to bring up find tool and type in the **first 3 digits of serial numbers**

  - once you find the section for your serial make sure the files you Select
    is compatible with your serial number by paying attention to **serial number range**
    below both flash files are for a 6NZ engine but only one of them is compatible with
    the serial range **6NZ12345**
    ![6nz-range1](images/6nz-range1.png)
    ![6nz-range1](images/6nz-range2.png)
## Section 4 Create work orders
