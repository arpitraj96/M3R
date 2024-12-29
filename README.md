# M3R
M3R is an IoT-based project focused on Monitoring, Metering, Mechanization, and Retrofitting. It integrates both hardware and software components to optimize lab management.

On the hardware side, the project is centred around the ESP32 microcontroller, which acts as the central hub for data processing and control. We utilized sensors like ZMPT101B and SCT013 to gather essential data for energy consumption monitoring and metering. The ESP32, running custom firmware I developed, collects and analyzes this data in real-time. This firmware also enables the microcontroller to make real-time decisions, such as controlling actuators that manage lab equipment. To facilitate mechanization, we incorporated relays into the system.

The entire hardware setup is connected to the cloud using Firebase RTDB and Firestore, enabling real-time data transmission. The software component is a mobile application built with React Native, which interfaces with the hardware through Firebase. This app allows users to monitor the status of lab equipment and control them remotely from anywhere.
