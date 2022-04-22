## Working of the project
In this project, an automatic room lighting system is developed using 8051 microcontroller. The working of the project is explained here.

The main component of the project is IR Sensor and we have used two of them. The placement of the sensors is important as it will determine the functioning of the project.

Practically speaking, both the sensors must be placed on the either side of the door or entrance of the room. The sensor placed on the outside of the room is named as Sensor 1 and the sensor, which is placed on the inside is named Sensor 2.

When a person tries to enter the room, Sensor 1 detects the person first and then Sensor 2. This action will indicate the 8051 Microcontroller that the person is entering the room.

Hence, the microcontroller will turn on the light and also increments the visitor counter to 1. If there are more visitor, the microcontroller will keep the light turned on and increments the visitor counter accordingly.

When a person tries to leave the room, Sensor 2 detects the person first and then Sensor 1. This process will make the microcontroller to understand that a person is trying to leave the room and hence, it will decrement the count of visitors. The microcontroller will not turn off the light until the last person has left the room.

As the visitors start leaving the room, the visitor count will be decremented and when the last person leaves the room, the count be comes 0. During this point, the microcontroller understands that there is nobody in the room and turns OFF the light.
