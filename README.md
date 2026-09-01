# ADXL345 e Input Shaper en Klipper

Proyecto complementario de **Ender AI** para medir resonancias con un ADXL345 y configurar Input Shaper.

## Contenido

- `config/adxl345-sonic-pad.cfg`: configuración del bus SPI usada como punto de partida en el sistema del video.
- `docs/`: guía en PDF (se agregará después de verificar el procedimiento).

## Importante

Los pines y el nombre del bus dependen del host y del método de conexión. La plantilla incluida corresponde al esquema encontrado en la configuración del proyecto de Ender AI; comprueba el pinout de tu placa antes de energizar el ADXL345.

Un ADXL345 normalmente trabaja a **3,3 V**. Una conexión incorrecta puede dañar el sensor o el host.

## Video relacionado

[Convertí mi Sonic Pad a Debian: Klipper + Eddy Duo + ADXL345](https://youtu.be/Kaymg9gaMvM)

## Fuentes oficiales

- [Medición de resonancias en Klipper](https://www.klipper3d.org/Measuring_Resonances.html)
- [Referencia de configuración Klipper](https://www.klipper3d.org/Config_Reference.html#adxl345)

## Licencia

MIT.
