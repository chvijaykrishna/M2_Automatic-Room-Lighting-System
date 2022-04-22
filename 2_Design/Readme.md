#### The project implemented here is one such project where the microcontroller based system automatically controls the room lights.

![image](https://user-images.githubusercontent.com/101176652/164609107-230c331c-c084-4ea1-94bc-5612fd046c77.png)

## Circuit Description
1) Let us see the design of the circuit for automatic room lighting project. The circuit diagram shows all the connections with respect to microcontroller. If you are doing this project on a development board, some of the connections mentioned in the circuit diagram might not be necessary.
2) Also, we have used modules for Relay and IR Sensor and hence, the connections are shown with respect to those modules only. Corresponding circuit diagrams are also provided.
3) Coming to the circuit design, a 16 x 2 LCD Display, two IR Sensors and a 5V Relay Module must be connected to the 8051 Microcontroller. First, connect the 8 data pins of the LCD to PORT1 pins i.e. P1.0 to P1.7.
4) The 3 control pins of LCD i.e. RS, RW and E are connected to P3.6, GND and P3.7 pins respectively. A 10 KΩ Potentiometer is connected to contrast adjust pin of LCD i.e. its pin 3.
5) Two Reflective type IR Sensors are connected to PORT2 pins i.e. P2.0 and P2.1. Detailed circuit of the IR Sensor is mentioned in the Component Description.
6) The input of the 5V Relay is connected to PORT0 pin P0.0. The detailed circuit of the 5V Relay module used in the project is explained in the component description section. Alternatively, you can construct the circuit as per the circuit diagram (which consists of 5V Relay, Transistor, Diode and a Resistor)

## Component Description
### IR Sensor Module
An Infrared or IR Sensor is a simple circuit that is used to detect objects (Proximity Sensor) or measure distance (Range Finder). An IR Sensor consists of 3 components: an IR Transmitter (IR LED), an IR Receiver (like a Photo Diode) and a signal processing circuit.
We have used reflective type IR sensor modules in this project. The detailed circuit diagram of the module is shown in the following image

![image](https://user-images.githubusercontent.com/101176652/164609042-96311e46-bc15-40c7-bd5b-a304ddbbdfaa.png)

### 5V Relay Module
A 5V Relay Module is used in this project which helps 8051 Microcontroller to operate high voltage AC loads like a light. The detailed circuit of the Relay Module is shown in the following image. It consists of a 5V Electromechanical Relay, an Optocoupler IC, transistor, two resistors and two diodes

![image](https://user-images.githubusercontent.com/101176652/164609079-81d06db6-d65c-4b6c-a7e5-e82ddcd013dd.png)
