# Prerequisites
You have to disable the automatic management of camera led in `/boot/config.txt`.  
```bash
$ sudo sh -c 'echo "disable_camera_led=1" >> /boot/config.txt' 
$ sudo reboot
```
# Quickly start

##  C++ version code

This demo supports Both cameras display at the same time

* Install the opencv library
```Bash
sudo apt-get install libopencv-dev
```
* Compile and run
```Bash
cd Multi_Adapter_Board_2Channel\c++

sudo make

sudo ./pi_zero_cam
```
### Runing Demo
![Alt text](https://github.com/ArduCAM/RaspberryPi/blob/master/Multi_Camera_Adapter/Multi_Adapter_Board_2Channel/data/demo.png)

## Shell version

This shell script is used to test each camera 
* Run the script
```bash
cd Multi_Adapter_Board_2Channel\shell
sudo ./pi_zero_cam.sh
```