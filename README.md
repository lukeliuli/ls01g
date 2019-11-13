镭神ls01g高校专用版的驱动程序，可以采集到/scan的周围环境信息，

Stop the scan command：
	rostopic pub /startOrStop std_msgs/Int32 "data: 1"

Stop the motor command（Stop the motor will stop scanning）:
	rostopic pub /startOrStop std_msgs/Int32 "data: 2"

Start scanning（Drive motor, and then open the scanning）：
	rostopic pub /startOrStop std_msgs/Int32 "data: 4"
