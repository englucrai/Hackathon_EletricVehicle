# Hackaton_EletricVehicle

Program to compute the speed profile and required power in a specific trajectory displayed in the archive "dataSet.csv" acquired via Strava App.

The dataset is made up of GPS coordinates and the time registered during the vehicle's route. The vehicle used in this challenge it's an AGIX Motor
Company golf car, 4 HP eletric engine, aeronautic chassis.

## Vehicle Specification

- Maximum Speed:	12 km/h

- Weight:	224 kg

- Batery Voltage:	48	volts

- Maximum power:	3,5	kW

- Wheel (diameter): 45 	cm

## Methodology

The route data was achieved via Strava App wich registers the vehicle's location (latitude, longitude and heigh) at each second using the integrated
GPS. The data is exported in SHP format, wich then was converted to .csv file. The final lenght of the route was 1.758 m and the time to completion 
was aproximatedely 312 seconds.

The Matlab program simulates the trajectory of the vehicle. The results are the speed profile and power required to move the vehicle, such as shown 
above.

![alt text](https://github.com/englucrai/Hackaton_EletricVehicle/blob/main/perfilvel.jpg)
![alt text](https://github.com/englucrai/Hackaton_EletricVehicle/blob/main/potencia.jpg)


