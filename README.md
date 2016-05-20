# Chronos-watch-controlled-car

EC535 Final project: TI chronos watch controlled robot car
Video link: https://www.youtube.com/watch?v=MuB2Obmotqk

INSTRUCTIONS

1. Make the kernel module located in km folder. 
2. Make the user level program called watchController in ul_acc folder. 
	insert the kernel module as follows.
	mknod /dev/mycar c 61 0
	inmod mycar.ko
then run the user level code and press the bottom right button on the watch to start sending data. 
