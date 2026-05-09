# esp8266-getting-started
Esse é um repositório de fim explicativo sobre as configurações necessárias para programar o microcontrolador ESP8266 NODE MCU 

# Configurando ESP8266
Dependendo da versão da placa, o chip responsável por essa conversão pode ser o CP210x (placas NodeMCU V2 e ESP32) ou o CH340G (placas NodeMCU V3). Neste tutorial você aprenderá como instalar o driver adequado e desta forma garantir que sua placa possa ser programada.

[site da robocore explicando drivers](https://www.robocore.net/tutoriais/instalando-driver-do-nodemcu)

## Instalando o Driver 

Configurando a Arduino IDE para Programar  ESP8266

📋 Requisitos

Você vai precisar :

- Cabo USB compatível com transferência de dados
- Placa ESP8266

## 🚀 Instalação da Arduino IDE

Baixe a versão mais recente da Arduino IDE:

[Arduino IDE Oficial](https://www.arduino.cc/en/software/)

Instale normalmente conforme seu sistema operacional.

## 🔧 Configurando suporte para ESP8266
1. Abra arduino IDE

    Arquivo → Preferências
2. Adicionar URL do ESP8266

No campo:

URLs Adicionais para Gerenciadores de Placas

Adicione:

https://arduino.esp8266.com/stable/package_esp8266com_index.json


3. Instalar pacote ESP8266

Na IDE arduino vá em:

Ferramentas → Placa → Gerenciador de Placas

Pesquise por: ESP8266

Instale:  esp8266 by ESP8266 Community

Depois selecione:

Ferramentas → Porta

Escolha a porta serial correspondente.

## Selecionando a placa correta
ESP8266

Exemplo:

Ferramentas → Placa → ESP8266 Arduino

Escolha:

ESP8266 Dev Module
ESP8266

Exemplo:

Ferramentas → Placa → NodeMCU 0.9(ESP-12 Module)

pronto!!

## Teste

vá em file -> exemplo -> ESP8266 -> blink

Este projeto pode ser utilizado livremente para fins educacionais e pessoais.
