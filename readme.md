# WS7_ESPHOME

En este repositorio se pretende usar [esphome](https://esphome.io/) y [lvgl](https://next.esphome.io/components/lvgl/) en una placa de desarrollo del fabricante Waveshare [ESP32-S3-Touch-LCD-7](https://www.waveshare.com/esp32-s3-touch-lcd-7.htm)

He tomado como referencia estos proyectos [ESP32-S3-Touch-LCD-7 ESPHOME LVGL HMI](https://github.com/bennydiamond/esphome_lvgl_hmi_garage) / [Waveshare ST7262 ESPHome LVGL](https://github.com/iamfaraz/Waveshare_ST7262_ESPHome_LVGL/tree/main)

![Inicio con lvgl](docs/img/20250909_lvgl.jpg)

Para poder usarlo, crea tu propio archivo secrets.yaml en el directorio ws7_esphome con los siguientes datos:

```yaml
# Your Wi-Fi SSID and password
wifi_ssid: "your_ssid"
wifi_password: "your_password"
``` 

Y ejecutar en el terminal el siguiente comando:
```bash
esphome run ws7_esphome.yaml
```


