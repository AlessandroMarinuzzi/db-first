# Dealer

## Cars

- id                            BIGINT          PRIMARY KEY UNIQUE NOTNULL      - 1
- Plate                         VARCHAR(12)     UNIQUE NOTNULL                  - GA861FK
- Brand                         VARCHAR(25)     NOTNULL                         - Nissan
- Model                         VARCHAR(25)     NOTNULL                         - GTR NISMO
- Color                         VARCHAR(25)     NOTNULL                         - Black
- Size                          VARCHAR(40)     NULL                            - 4.690 mm length x 1.895 mm width x 1.370 mm height
- Weight(Kg)                    SMALLINT        NULL                            - 1725                    
- Design                        VARCHAR(25)     NULL                            - Coupé 
- Engine                        VARCHAR(30)     NULL                            - 3,8 l V6
- Gear                          VARCHAR(15)     NOTNULL                         - 6-speed Automatic
- Traction                      VARCHAR(20)     NULL                            - 4x4 all-wheel drive
- Fuel                          VARCHAR(25)     NOTNULL                         - Petrol
- Consumption                   VARCHAR(30)     NULL                            - 14 l/100km average (18 urban, 11 suburban)
- CO2 Emissions(g/Km)           SMALLINT        NULL                            - 275
- Euro Class                    TINYINT         NOTNULL                         - 5                 
- Displacement(cm³)             FLOAT(4,3)      NOTNULL                         - 3.799
- Horsepower(HP)                SMALLINT        NOTNULL                         - 600
- Weight/Power ratio(kW/kg)     SMALLINT        NOTNULL                         - 441
- Engine Torque(N·m)            SMALLINT        NULL                            - 652
- Max Speed(Km/h)               SMALLINT        NULL                            - 315
- Kilometers                    MEDIUMINT       NOTNULL                         - 14500
- Release Year                  YEAR            NOTNULL                         - 2020
- Previous Owners               TINYINT         NULL                            - 1
- Accidents                     TINYINT         NULL                            - 0
- Engine Restored               BOOLEAN         NULL                            - 0
- Car Review                    YEAR            NULL                            - 2020
- Description                   TEXT            NULL                            - "The car has no damage to the bodywork. 
                                                                                   Never crashed.There are no losses.
                                                                                   The interiors are intact.
                                                                                   General condition of the car is very good."
- Price                         DECIMAL(10,2)   NOTNULL                         - 168000.00
- Notes                         VARCHAR(30)     NULL                            - "Price is not negotiable"