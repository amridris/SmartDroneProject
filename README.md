
This Github repositry is dedicated for the Smart Agriculture Drone project which contains the source code of the Ground control station. The team decide to use the QgroundControl open source software to implement the drone autonomous features as well as controlling the drone. The team has tweaked the software GUI to reflect the agriculture features worked on by the team. 

Project Advisor:
Dr Jerry Gao 

Project Members: 
Aamer Idris
Jacob Jones
Brandon Nguyen
Bibek Shrestha



**Software Build Instructions

The software supports all of the major operating system Windows, MacOs, Linux, Android, and iOS. QGC uses Qt as a cross platform libraries as well as compiling using Qt creator build environment. 

After installing Qt, run the Qt creator and choose the appropriate supported compiler to build the source depending on the running operating system:

OSX: Desktop Qt 5.11.3 clang 64 bit
Ubuntu: Desktop Qt 5.11.3 GCC 64 bit*
Windows: Desktop Qt 5.11.3 MSVC 2015 32 bit*
Android: Android armeabi-v7a (GCC 4.9, Qt 5.11.3)

Once the appropriate compiler is chosen run the build command in Qt to compile and run the program.




**Notes:

Ubuntu Linux: may need to run the following command to avoid compilation error

sudo apt-get install speech-dispatcher libudev-dev libsdl2-dev

Windows: USB Drivers to connect to pixhawk Radio (http://pixhawk.org/firmware/downloads)

Android: Install Qt Android 



Credits
This application uses Open Source components. You can find the source code of their open source projects along with license information below. We acknowledge and are grateful to these developers for their contributions to open source.

Project: 

Mavlink/QGroundControl (https://github.com/mavlink/qgroundcontrol)
Apache 2.0 License
GPL v3 License
