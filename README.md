# ESPhome-alarm

Copy contents of secrets.yaml to your cconfig\secrets.yaml file changing SSid and Password to your own

Copy contents of ESPhome folder to your config\ESPhome\ folder

flash nodeMCU with alarm_pir.bin file attached 

in home assiatnt goto ESPhome and alarm_pir should be showing

add to Home assistant via Intergrations.
Click +
select ESPhome
type alarm_pir.local (or use esp IP address) and click submit
follow on screen instructions
you should now have multiple sensors called:
binary_sensor.tamper
binary_sensor.motion_zone1
binary_sensor.motion_zone2
binary_sensor.motion_zone3
binary_sensor.motion_zone4



