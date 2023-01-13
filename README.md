## TUYA-ARGO-3S

| # | Function | GPIO |
| - | ------- | ------ |
| 5 | SW2   | GPIO14 |
| 6 | SW1   | GPIO12 |
| 7 | CTRL1 | GPIO13 |
|8 | VCC | |
|9 | GND | |
| 10 | CTRL3 | GPIO15 |
| 13 | CTRL2 | GPIO4 |
| 14 | SW3   | GPIO5 |

## ESPHome

```
docker run --rm --net=host -v "${PWD}":/config -it esphome/esphome
```

- https://peyanski.com/complete-esphome-installation-guide/
