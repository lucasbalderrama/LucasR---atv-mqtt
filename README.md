# Explicações necessárias para preparação de ambiente (incluindo biblioteca necessária) e passo a passo para testar.

### O 1° passo é instalar a biblioteca Paho-MQTT, pois é ela que permite utilizar o MQTT em Python:

#### Instalando a biblioteca (prompt de comando ou terminal):

pip install paho-mqtt

### O 2° passo é criar um servidor MQTT para receber mensagens, o que está sendo feito no arquivo subscriber.py (que está no repositório), após criar o servidor:

* Execute o programa em um terminal Python;
* O código ficará rodando e exibindo mensagens que forem envadas no tópico senai/dev;

### O 3° passo é criar um servidor MQTT para enviar mensagens, o que está sendo feito no arquivo publisher.py (que está no repositório), após criar o servidor:

* Execute o programa em outro terminal Python;
* Digite mensagens no console e pressione __enter__ para envia-lás;
* O primeiro servidor (que recebe as mensagens - subscriber.py) exibirá as mensagens;

### Finalizando os testes, encerre o terminal.
