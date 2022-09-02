# DT community WI-FI Reader
This is a community built board that helps make use of NFC implants. The inital design was made with Home Assistant in mind and follows [this previouse project](https://github.com/adonno/tagreader). This repo is more for board designs and optomising the readers to work best with implanted devices.

## How to mod the board your self
1) Download and install [EasyEDA](https://easyeda.com/) 
2) Open this project in Easy EDA
    1) File -> Open -> EasyEDA -> (location you clones this repo into) -> 8266 NFC reader -> 8266 NFC reader.json
    2) It will then open the schematic for the board. Any changed made will need to update the PCB. In the top menu, Design -> Update PCB -> No, Keep Going
    3) In the menu on the left you will also see a file called 'PCB_8266 NFC reader' open that to show the full board design with traces
3) Once you add or remove anything you want you can use the built in JLCPCB integration to have boards ordered, or you can export the Gerber files and have the boards made anywhere.
    1) You must be in the PCB design file and then go to Fabrication -> PCB fabrication files(gerber)
    
## Design talk
![schematic design](images/schematic.png)
