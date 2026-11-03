# RosDuino

**ROS 2 for Arduino.** A sketch on the board publishes, subscribes, and calls services. [rosduino_agent](https://github.com/rosduino/rosduino_ros) on the computer turns that board into an ordinary ROS 2 node over USB or UART. [rosduino_arduino](https://github.com/rosduino/rosduino_arduino) is the library; [rosduino_ros](https://github.com/rosduino/rosduino_ros) is the agent and `rosduino-gen`, which writes headers for your own `.msg` and `.srv` files.

Tested Boards: Arduino Nano, Uno, Micro, Mega 2560, and Due. The computer needs ROS 2 Lyrical (recommended) or Jazzy. Install the library from [Releases](https://github.com/rosduino/rosduino_arduino/releases), flash **File → Examples → RosDuino → Simple → Led**, and start the agent on the same port. License: [Apache-2.0](https://github.com/rosduino/rosduino_arduino/blob/master/LICENSE).

**Ultra simple API**  [LightSensor.ino](https://github.com/rosduino/rosduino_arduino/blob/master/examples/Simple/LightSensor/LightSensor.ino)
