<h3>ESPHome based PWM fan controller</h3>
This fan controller uses the ESP32 Control Board Ver. 2.1 <br>
<a href="https://www.tindie.com/products/esp32/esp32-control-board-ver-21/">
https://www.tindie.com/products/esp32/esp32-control-board-ver-21/</a><br>
and adds an expansion module with a display and two rotary encoders.<br>
<br>
The fan controller works without any USB or Internet connection and allows the user to view
all relevant data and set all necessary parameters.<br>
Additionally, the user may connect to the module via Wifi and remotely view more data and change settings, if desired.<br><br>

<div align="center">
    <img width = "40%" src="images/fc01.jpg">
    <img width = "30%" src="images/fc02.jpg">
</div>


The left button changes the temperature at which the fan turns off<br>
the right button changes the temperature at which the fan runs at full speed.<br>
<div align="center">
    <img src="images/fancurve.png" alt="fancurve" width="400">
</div>
<br>
<h4>Circuit Diagram</h4>
<div align="center">
    <img src="designfiles/KiCAD/schematic.png" alt="Alt Text" width="500">
</div>
<br>
<h4>Parts</h4>
<img src="images/enc.jpg" alt="encoder" width="200">
<a href="https://www.amazon.com/dp/B07T3672VK">
https://www.amazon.com/dp/B07T3672VK</a><br>
<br>
<img src="images/display.png" alt="display" width="200">
<a href="https://www.amazon.com/dp/B0C9LJ898Z">
https://www.amazon.com/dp/B0C9LJ898Z</a><br>

<h4>Source Code</h4>
<a href="https://github.com/atmelino/fancontroller/tree/main/sourcecode/ESPHome">
https://github.com/atmelino/fancontroller/tree/main/sourcecode/ESPHome</a><br>

