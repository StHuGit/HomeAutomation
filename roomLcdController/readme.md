LCD room controller based on ESPHome and integrated to Home Assistant
**Components**
- lilygo ttgo t-4 http://www.lilygo.cn/prod_view.aspx?TypeId=50032&Id=1159
- BME280 preassure, temperature and humidity all-in-one i2c sensor 

**Configuration parts**
- ESPHome yaml, display configuration and layout
- Pictures folder with icons for display
- Font folder with font for display
- Home Assistant sensor yaml to extract data from weather plugin

**Future changes**
- Wooden frame next to lightning switch
- replace BME280 by combination of CCS811 + SI7021 + BMP280 to expand capability for measuring CO_2 and efectively control recuperation unit.
