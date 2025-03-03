# BuzzMeter

## Pt-Br

O BuzzMeter é um aplicativo desenvolvido para monitorar as condições internas de uma colmeia de abelhas, garantindo o bem-estar das abelhas e a eficiência da produção de mel. O sistema irá medir a temperatura, a umidade e a pressão atmosférica dentro da colmeia, permitindo ao apicultor acompanhar em tempo real as condições ambientais e tomar ações preventivas, se necessário.

Para a coleta dos dados, será utilizado o ESP32, um microcontrolador com conectividade Wi-Fi que ficará responsável por captar as informações dos sensores (como sensores de temperatura, umidade e pressão) instalados na colmeia.

A comunicação entre o ESP32 e o aplicativo será feita através de uma API RESTful desenvolvida com o Flask, um framework leve e eficiente para criar servidores web. O Flask será utilizado para gerenciar as requisições e fornecer as informações coletadas pelo ESP32 em uma interface simples e intuitiva para o usuário.


## En-Us

BuzzMeter is an application developed to monitor the internal conditions of a beehive, ensuring the well-being of the bees and the efficiency of honey production. The system will measure temperature, humidity, and atmospheric pressure inside the hive, allowing the beekeeper to track environmental conditions in real time and take preventive actions if necessary.

To collect the data, the ESP32, a microcontroller with Wi-Fi connectivity, will be used. It will be responsible for gathering information from sensors (such as temperature, humidity, and pressure sensors) installed inside the hive.

Communication between the ESP32 and the application will be done through a RESTful API developed using Flask, a lightweight and efficient framework for creating web servers. Flask will be used to manage requests and provide the data collected by the ESP32 in a simple and intuitive interface for the user.


