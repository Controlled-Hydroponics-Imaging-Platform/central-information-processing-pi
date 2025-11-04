# central-information-processing-pi
handles the information flow of the controlled hydroponic imaging platform 




### MQTT Server:


Mosquitto Broker
```bash
sudo apt install -y mosquitto mosquitto-clients

sudo systemctl enable mosquitto
sudo systemctl start mosquitto

sudo nano /etc/mosquitto/mosquitto.conf
```

``` yaml
listener 1883
allow_anonymous true
``` 

```bash
sudo systemctl restart mosquitto
```


### RPI info

hostname: pi@infoprocessing.local