# UnitreeMotorSDK_M80106
To control the M80106 motor, you need to prepare a `Unitree USB to RS485 module`.

- System Requirements  
Ubuntu 18.04 recommended, not a virtual machine.
- Development Environment Requirements  
`sudo apt install git build-essential cmake` 
## SDK using example  
`git clone https://github.com/OnlineMC/UnitreeMotorSDK_M80106.git`  
`cd UnitreeMotorSDK_M80106`  
`mkdir build`  
`cd build`  
`cmake ..`  
`make`  

## Motor Running  

Now, access to motor power supply and communication lines.  
`sudo ./motorctrl`  
