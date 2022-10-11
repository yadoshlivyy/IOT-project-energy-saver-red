# IOT-project-energy-saver-red
Energy Saver IOT project (Summer 2022)
## Team Members:
Maxim Yadoshlivvy  
Ran Semel  
Ward Mouallem
## Project Links:
  * [Link to Project Activation & documentation](https://beautiful-thorn-cdf.notion.site/IOT-Project-Documentation-26e425b2943d4ef78d1500706d3db0ea)
  * [Link to Agile management](https://beautiful-thorn-cdf.notion.site/IOT-Project-Agile-management-7e3c0a345f154c57bb63119a784a9c95)
## Project Files:
  * ac-remote.yml - The ESPHome coniguration file. It will be compiled into the firmware that will run on the ESP32 board. Here we define the sensors, buttons and the logic behind the automations.
  * automations.yaml - Here we define the automations on the HomeAssistant side that interact with the sensors on the HomeAssitant dashboard.
  * configuration.yaml - This is the HomeAssistant configuration file, here we can define different, buttons and sensors(like user input) that will appear on the dashboard and ESPHome can interact with.
## Project Story:
Open source smart remote , that can recieve remote commands and can be used with automations.
## Project features:

### Basic features:
* Send ON/OFF command via Remote Application
* Automations based on Temeprature sensor data

### Advanced features:
* Home Assistant integration
* Learning mode - give user possibility to insert it's own IR signal
* Multi Sensor / error detection mode - show all sensors state, in case if some sensor unavailable give indication in HA ( Home Assistant )
* Multiple ACs support
* Notifications support - status of AC via Telegram bot
* Automations based on user input
