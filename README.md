# Features
* A cheap very simple solar lamp. Can be 3D printed, or built in a glass jar.
* Automatically switch on/of the light when night/day comes
* Solar
* Can be switched off manualy, and used as a torch
* Printable circuit board (KiCad)

# Pictures
<img src="https://raw.githubusercontent.com/pierreblavy2/elec-solar_lamp/main/images/photo-day.jpg" height="125px"> <img src="https://raw.githubusercontent.com/pierreblavy2/elec-solar_lamp/main/images/photo-night.jpg" height="125px"> <img src="https://raw.githubusercontent.com/pierreblavy2/elec-solar_lamp/main/images/screen-pcb.jpg" height="125px">

# Components

|Name|Quantity|Description|
|---|---|---|
|QX5252|1|https://datasheetspdf.com/pdf/719492/Qxmd/QX5252/1|
|AAA_holder|1|AAA battery holder|
|Solar_panel|1|60x60 mm, 5V|
|5mm LED|1|20mA LED|
|330uH|1|Inductance DIP (1)|
|Switch|1|20mm, toggle, on/off (2)|
|5mm LED support|1|RTM5021|

(1) Inductance values control the currant going trough the LED, according to this table
|Inductance (uH)|Current (mA)|
|---|---|
|330|11|
|270|14.5|
|220|15.5|
|150|25|
|100|34.5|
|82|38|
|56|50|
|47|75|
|33|110|

(2) The switch is mounted in series with the LED


