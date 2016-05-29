# DistanceMeasurement-SonarSensor
Measue Object Distance with Sonar Sensor HC-SR05

Code>
    equation solve!
    
    The speed of sound is 343m/s    [m/s=meters per second]
    1/343[s/m] x 1[m]/100[cm]=2.915E-5[s/cm]        where [s/m]=[seconds per meter], [s/cm]=[seconds per centimeter]
    Now convert to microseconds per cm:
    2.915E-5[s/cm]x1000000[us/s]=29.15[us/cm], where [us]=[microseconds] [ms/cm]=[microseconds per centimeter]﻿
    
    
    or easy solution!
    
    D = T * V
    29.1 = 1/V
    so  D = T / (1/V) = T * V
