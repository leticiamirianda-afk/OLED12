# ESP32 com Display OLED

Projeto utilizando um **ESP32** para exibir uma mensagem em um display **OLED 128x64** através da comunicação **I2C**.

## 📚 Bibliotecas utilizadas

* `Wire.h` — comunicação I2C
* `Adafruit_GFX.h` — recursos gráficos
* `Adafruit_SSD1306.h` — controle do display OLED

## ⚙️ Funcionamento

Ao iniciar o ESP32, o programa:

1. Inicia a comunicação serial.
2. Inicializa o display OLED no endereço `0x3C`.
3. Define o tamanho e a cor do texto.
4. Limpa a tela.
5. Exibe a mensagem **"Leticia Cardoso"** no display.

## 🖥️ Display

* Largura: **128 pixels**
* Altura: **64 pixels**
* Comunicação: **I2C**
* Endereço: **0x3C**

## 🔌 Componentes

* ESP32
* Display OLED 128x64
* Cabos jumper

## 🎯 Objetivo

Aprender a utilizar um display OLED com ESP32 através da comunicação **I2C**, mostrando uma mensagem na tela.
