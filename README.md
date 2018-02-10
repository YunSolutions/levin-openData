# LEVIN-Open Data

LEVIN Vehicle Telematics Data

Current version: v1.1

Owner – Yuñ Solutions

Data Updated – 10th Feb 2018

# What is it?

Yuñ Solutions is an India based start-up with its head office in Pune. We are into IoT domain where we collect data about driving and vehicle using our flagship product LEVIN. At Yuñ Solutions, we are committed to democratizing technology and make information accessible to all. 

The data is collected using various sensors. The accelerometer sensor gives us insights on acceleration and deceleration, magnetometer tells us about the direction w.r.t earth’s magnetic field and gyroscope gives us insight about rotation.

# What is OBD?

[On-board diagnostics](https://en.wikipedia.org/wiki/On-board_diagnostics) (OBD) is an automotive term referring to a vehicle's self-diagnostic and reporting capability. OBD systems give the vehicle owner or repair technician access to the status of the various vehicle subsystems.

OBD-II is an improvement over OBD-I in both capability and standardization. The OBD-II standard specifies the type of diagnostic connector and its pinout, the electrical signalling protocols available, and the messaging format.

# About Dataset

The dataset provided here is a sample data for data we collect real-time. This dataset is collected for over a 4 month period on approximately 30 4-wheelers. We collect OBD data at 1Hz frequency (1 record per second) while accelerometer data is collected at 25 hz (25 data points per second)

This metadata includes – Device Id, timestamp, trip id, accelerometer data, speed gathered from GPS, battery voltage, coolant temperature, diagnostic trouble codes, engine load, intake air temperature, manifold absolute pressure, calculated mileage, mass airflow, engine RPM, speed collected from OBD, timing advance, throttle position and magnetometer data.

The full data set is available as

1. [A Single CSV](https://mega.nz/#!PJxlCKDB) and [another Single CSV with more obd parameters](https://mega.nz/#!CV5lQbBZ)

2. [A Single SQLite3 Database](https://drive.google.com/open?id=1tJd8oosfpY_l2DPXiaFRObOBhCa2gFc-)

3. [A Single Compressed Zip with individual CSVs](https://drive.google.com/open?id=1T0M_7585gl8h-wcCyfBdDQVaTXKbVdw8)

4. [Individual CSVs](https://mega.nz/#F!TE50HRyK!VTGi_U9KhsS-JJHBRzKKwA) This link will be updated monthly from now onwards

# How to use

The dataset can help in various kind of analysis including,

1. Driving patterns

2. [Gear Detection](https://github.com/YunSolutions/levin-openData/tree/master/gear-detection)

3. Events like hard brakes, hard acceleration, sharp turns and lane changes

4. Impact detection 

Since, dataset contains data collected at different frequencies, it can a task to combine them and use them together. The dataset contains accelerometer data in raw format, to make sense of the data and convert it to usable format, please refer to data_extract.ipynb file.

# More about Yun
Website - [www.yun.buzz](www.yun.buzz)

# More about LEVIN
webpage - [levin.yun.buzz](levin.yun.buzz)



LEVIN Vehicle Telematics Data by Yun Solutions is licensed under Creative Commons BY-NC-SA License. 




