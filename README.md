# garage-door  



**Depenancies:**

- elcipse-mosquitto (mqtt)

  - https://hub.docker.com/_/eclipse-mosquitto/

- ###### pi-mqtt-gpio  

  - https://github.com/flyte/pi-mqtt-gpio 
  - pip install pi-mqtt-gpio

**How to:**

1. pip install pi-mqtt-gpio
2. copy gpio_mqtt.service to "/etc/systemd/system/"
3. run "systemctl enable gpio_mqtt.service"
4. run "systemctl start gpio_mqtt.service"