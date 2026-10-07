# MatrixClock_ESP32C3_6xMAX7219
based on https://github.com/schreibfaul1/ESP8266-LED-Matrix-Clock/ and https://github.com/tehniq3/ESP8266-LED-Matrix-Clock/ but changed for ESP32-C3 Supermini

my article: https://nicuflorica.blogspot.com/2026/10/ceas-ntp-pe-6-matrici-de-8x8-leduri.html


ESP32-C3 SuperMini       MAX7219
--------------------------------
- GPIO4  ----------------> CLK
- GPIO6  ----------------> DIN
- GPIO7  ----------------> CS
- GND    ----------------> GND
- 5V     ----------------> VCC

![schematic](https://blogger.googleusercontent.com/img/a/AVvXsEhFIA3SE0goEljw3tcJPUGhksKl0NDvGKFQSEmP24p6PyQQt3fetB6KQNj3fB4asxDCd8zAiK_W3cFKoDRUzpfXWPG2o2ZgS8PrNB38RWBBjsHYgJrmvI3VO2-uokiQIu8jN5wGNvGzPCjki9Z_-Wi_H4SLtnsQSYJXUIkx0Im1AkQ0VPItxl7KDN9C2J3-)
