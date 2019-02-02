# Azure-Event-Hubs-PoC

* Clone this repo
* Change to the cloned directory
```cd Azure-Event-Hubs-PoC```
* Skim https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-node-get-started-send
* Follow the Azure console instructions to create a Kafka-enabled topic
* Run the initialize shell script
```shell
chmod 755 initialize
chmod 755 poc-produce
initialize
```
* Follow the .env configuration steps
* Run the poc-produce shell script
```shell
poc-produce
```
