# rdino
rp-2040 development board in the shape of arduino uno r3 so it supports its hats and also has esp32 for wifi and bluetooth and 5x5 grid of neo pixel leds

it has dual microcontroller so all the less important repetative tasks can be off loaded to esp32 and main work can be done by the rp 2040 chip with extra 16M bit memory
and it can be used foor any project like lfr robot , micromouse , rc car etc

<img src="Screenshot (1535).png" alt="PCB Layout 1" width="600">

<img src="Screenshot (1530).png" alt="PCB Layout 1" width="600">

<img src="Screenshot (1531).png" alt="PCB Layout 2" width="600">

<img src="Screenshot (1532).png" alt="DRC Errors" width="600">

<img src="Screenshot (1533).png" alt="Silkscreen Design" width="600">

<img src="Screenshot (1534).png" alt="3D View" width="600">


## BOM
| Component | Purpose | Qty | Cost (USD) | Distributor |
|---|---|:---:|:---:|---|
| [Seeed Studio XIAO ESP32-S3 Sense](https://www.seeedstudio.com/XIAO-ESP32S3-Sense-p-5639.html) | Camera and controller | 1 | $25.00 | Seeed Studio |
| [MPU-6050](https://www.aliexpress.com/item/1005007986741850.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000043166583348%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Gyroscope / IMU | 1 | $7.20 | AliExpress |
| [Motors](https://www.aliexpress.com/item/1005006105092170.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000035766688570%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Spin propellers | 1 | $5.77 | AliExpress |
| [Propellers](https://www.aliexpress.com/item/1005005351811890.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000032714337732%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Provides lift | 1 | $5.90 | AliExpress |
| [Battery](https://www.aliexpress.com/item/1005006762177546.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000038217592894%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Power source | 1 | $6.50 | AliExpress |
| [Battery Connector](https://www.aliexpress.com/item/1005003431613901.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000028261810379%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Connects battery to PCB | 1 | $3.20 | AliExpress |
| [Transistors](https://www.aliexpress.com/item/1005011574380229.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000055960036705%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Motor switching (SI2300DS) | 1 | $2.50 | AliExpress |
| [Diodes](https://www.aliexpress.com/item/1005007160563285.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000039653324544%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Flyback protection (1N4148W) | 1 | $2.20 | AliExpress |
| [Resistors](https://www.aliexpress.com/item/1005010519485476.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000052676754449%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Pull-down / voltage divider | 1 | $4.10 | AliExpress |
| [Capacitors](https://www.aliexpress.com/item/1005007470747384.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000040888645899%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Motor decoupling | 1 | $1.90 | AliExpress |
| [LED](https://www.aliexpress.com/item/1005010338676055.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000052257941480%22%7D&sourceType=1&spm=a2g0o.wish-manage-detail.0.0) | Status indicator | 1 | $5.20 | AliExpress |
| PCB | Component mounting | 1 | $4.30 | JLCPCB |

**Total Estimated Cost: ~$73.77**
