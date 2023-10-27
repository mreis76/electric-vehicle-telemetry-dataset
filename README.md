# electric-vehicle-telemetry-dataset
A dataset of electric vehicle telemetry data

This dataset was collected in October 2023, from a JAC IEV40 electric vehicle.

We made nine trips, with nine different drivers, with the same route. We started in Poços de Caldas, MG, Brazil, went to São João da Boa Vista, SP, Brazil and returned to Poços de Caldas. The trips with drivers #6 and #9 had interruption in the data transmission, resulting in loss of data, thus those trips are incomplete.

The features we collect are:
- id: unique identification of the data
- COND: driver number
- LAT: latitude
- LON: longitude
- ALT: altitude, in meters
- AX,AY,AZ: accelerometer (X, Y and Z axis), 2048 LSB/g
- GX,GY,GZ: gyroscope (X, Y and Z axis), 16.4 LSB/(º/s)
- Y,M,D,H,MIN,SEC: timestamp of the GPS, UTC
- CH: battery charge, in percentage
- VOL: voltage
- CUR: electric current
- SPD: instantaneous velocity
- ODO: odometer
- BRK: break pedal tilt
- ACC: accelerator pedal tilt
- AUT: indicated autonomy, in kilometers
- ECO: economy mode (0 - inactive, 192 - active)
- AIR: air conditioning (0 - off, 2 - on)

