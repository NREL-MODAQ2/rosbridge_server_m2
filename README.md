This is a modified version of https://github.com/RobotWebTools/rosbridge_suite


The only modification that has been made was turning "delay_between_messages = 0" into "delay_between_messages = 0.0" so we can get faster update rates to the web based HMI. This change is in     rosbridge_suite/rosbridge_server/src/rosbridge_server/websocket_handler.py

Using the standard release of rosbridge_server would be fine if you are not in need of update rates on the HMI less than 1 sec.
