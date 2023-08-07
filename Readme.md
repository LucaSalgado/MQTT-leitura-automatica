# Programa de teste para comunicação automática via MQTT ao ESP8266.

### Este arquivo de teste descreve um programa de envio de mensagens automáticas via MQTT.

## Componentes

Neste teste temos acoplado ao ***nodeMCU ESP8266***: 
- um dht11;
- um dht22;

## Bibliotecas

- PubSubClient;
- DHT sensor library;
- ESP8266WiFi.

## Links úteis

- [ESP Primeiros Passos](https://www.youtube.com/playlist?list=PL7CjOZ3q8fMe6DxojEFuDx4BP0qbbpKtP) - Além de ensinar o Básico de programação para o ESP8266 ele também ensina um pouco de comunicação MQTT na prática.

Caso queira testar o envio e o recebimento das mensagens via MQTT - Os dois links ensinam a instalar o cliente MQTT chamado mosquitto, e com ele tanto se inscrever(subscribe) quanto publicar(publish) em tópicos do broker MQTT.
- [Implementando um Subscriber](https://cadernodelaboratorio.com.br/2018/12/10/implementando-um-subscriber-mosquitto/)
- [Implementando um Publisher](https://cadernodelaboratorio.com.br/2018/12/07/implementando-um-publisher-mosquitto/)

## Atenção

É necessário que ajuste os parametros da configuração do WiFi para que o ESP8266 se conecte a sua rede.

Parametros do MQTT devem ser únicos para que não haja qualquer conflito com algum já existente.

O ESP8266 somente irá mandar informações no formato de **plain text**.
