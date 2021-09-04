# IOT - Internet of things

### Atributos que o cliente deve considerar em suas escolhas:
- Baixo consumo de energia;  
- Rede de dados limitado;  
- Resiliencia;  
- Segurança;  
- Customização;  
- Baixo custo.

### Arduino:
- Plataforma de prototipagem;  
- Com entradas/saídas;  
- Desenvolvedor escreve em C/C++;  
- Interface serial ou USB;  
- Shields;  
- Não tem conexão com a internet.  

### Embarcados (MCU's):
- Microcontrolador de chip unico;  
- Sistema operacional real time;  
- Embarcado;  
- Uso industrial, medico, militar, transporte.

### Minicomputadores (Raspberry Pi):
- Computador completo;  
- Hardware integrado em uma única placa;  
- Roda SO Linux ou Windows;  
- Uso domestico ou comercial.

## MQTT
- Protocolo de comunicação única;  
- Protocolo mais utilizado dentro dos IOT's;  
- Base na pilha do TCP/IP;  
- Protocolo de menssagem assincrona (M2M);  
- Criado pela IBM para conectar sensores de pipeline de petróleo a satélites;  
- Padrão OASIS suportado pelas linguagens de programação mais populares;  
- Modelo Publish/Subscribe

### Exemplo de topico:
mqtt://broker.io/a6g3I9/gps/position:

mqtt = protocolo;  
broker.io = broker;  
a6g3I9 = user identifier;  
gps = sensor;  
position = information type.  

## QoS
- Garantias de que as mensagens do broker estão sendo entregues;
- Separado por níveis

### QoS 0
- Nivel minimo de menor esforço
- Sem garantia de entrega
- Mensagem não é retransmitida

### QoS 1
- Mensagem é armazenada no client e publica para o broker, que responde que recebeu e armazenou essa mensagem;  
- Mensagem pode ser retransmetida para o broker se não ocorrer a confirmação de entrega
- nivel mais usado;

### QoS 2
-Nivel mais seguro e mais caro;  
-Garante que a mensagem foi entregue no minimo uma vez ao recebedor;  
- Mensagem pode ser retransmetida para o broker se não ocorrer a confirmação de entrega  

# CLOUD
- Grande e cada vez maior o número de devices conectados;  
- TB's ou PB's de informações;  
- Potencial de escala global.

### Empresas Cloud's providers:
-Amazon (AWS);  
-Microsoft;  
-Google;  
-Oracle;  
-IBM;  
-Alibaba Cloud.  

# Prova de conceito

*Thing -> broker -> Worker -> DataStore
* GPS -> Mosquito -> Node.js -> MySQL
