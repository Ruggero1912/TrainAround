# TrainAround

TrainAround is an android app that let a trainer control the training status of a group of athletes.

## Hardware Architecture

The athletes should wear a WearOS watch with the TrainAround-client app installed and running, while the trainer can use an android phone or tablet to control the training status of the athletes in real-time.

## Gathered data

- Step Counter (build-in sensor)
- Heart Rate (build-in sensor)
- Speed (using GPS)
- Distance (using GPS)
- Pace (using GPS, defined as $Time \over Distance$)

We also used the Activity Recognition API to determine the state of the athlete that can be:

- Still (no activity recognized)
- Walking
- Running

## Network architecture

Our focus was also on the network to connect the smartwatches to the Coach's Smartphone (central hub). We end-up developing a Bluetooth Low Energy (BLE) Star Topology Network. 

Part of our work involves the choice of this solution comparing it to other alternatives in terms of Compatibility, Versatibility, Simplicity and Energy Efficiency.

![network architecture](_images/startopology_network.png)

## User interface

![user interface](_images/user_interface.png)

