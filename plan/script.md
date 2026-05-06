
# Diagram of Connections

Diagram of the connections between the OLED display, ESP32-S3-DevKitC-1, and TCS3448 sensor:

    OLED Display           ESP32-S3-DevKitC-1           TCS3448 Sensor
      +-----------+         +-------------------+         +-----------+
      |  GND -----|---------| GND           VIN |---------| GND       |
      |  VCC -----|---------| 3V3           SCL |---------| SCL       |
      |  SCL -----|---------| GPIO9         SDA |---------| SDA       |
      |  SDA -----|---------| GPIO8             |         +-----------+
      +-----------+         |                   |
                            |                   |
      [Button1]---GPIO0-----|                   |
      [Button2]---GPIO1-----|                   |
      [Button3]---GPIO2-----|                   |
      [Button4]---GPIO3-----|                   |
      [Button5]---GPIO4-----|                   |
      [Button6]---GPIO5-----|                   |
                            |                   |
                            +-------------------+

# Materials Needed

1. [主控开发板MCU(带Wifi蓝牙模块) -- 30元]（）


1. [特氟龙胶带（用于冒充余弦矫正器，非必须）-- 40元](https://detail.tmall.com/item.htm?ali_refid=a3_430673_1006%3A1110415788%3AH%3AG50v4UWZU577n491tHDTMw%3D%3D%3Adce20a8be153b65214253cf3bb4da993&ali_trackid=282_dce20a8be153b65214253cf3bb4da993&id=43495171390&loginBonus=1&mi_id=00008jkHY4iDQezJuCvzIc5PbyJbwMkwnnxxOMg-2MCRUQY&mm_sceneid=1_0_106893773_0&priceTId=214784f817780472444338192e1213&skuId=3452622759935&spm=a21n57.sem.item.1&utparam=%7B%22aplus_abtest%22%3A%22ae4b340b7be39c5459d59f548045e234%22%7D&xxc=ad_ztc)


# Problems

1. 数据存储问题
2. 开发环境配置
3. 数据烧录问题




