# Lixeira inteligente

# Informacoes gerais
* Universidade Presbiteriana Mackenzie 
* Nome: Allan Lopes Ferreira
* TIA: 20009399 
* Disciplina: Objetos Inteligentes Conectados 
* Profº: Dr. Wilian Franca Costa 

# Descrição do Projeto
Este projeto;artigo científico é a estruturação de uma pesquisa relacionada a Internet das Coisas (IoT) e sua aplicação na área residencial e/ou comercial. Após análise, vive-se numa mudança de hábitos e paradigmas por conta da pandemia causada pelo Corona vírus (sars-cov-2), obrigando a sociedade como todo a reeducação de alguns hábitos, banais, como abrir um cesto de lixo. O estudo propõe aplicação pratica de automação de abertura de cestos de lixo, assim, evitando o contato e possível contaminação – residencial e até em hospitais, utlizando tambem o protocolo MQTT para acionamento remoto.

Montagem do projeto
(colocar imagem)

# Componentes utilizados
- 1 Cesto de lixo basculante;
- 1 Sensor ultrassónico HC-SR04;
- 1 NodeMcu ESP-8266 CH340G;
- 1 Micro Servo 9g SG90;
- 2 Protoboard 400 pontos;
- 1 Bateria 9v

# Especificacao Tecnica
O desenvolvimento do codigo foi utilizado a IDE Arduino e a linguagem C++. Para o desenvolvimento sistemico, fora utilizados as seguintes bibliotecas, disponiveis na IDE do Arduino:
* <Servo.h> - Biblioteca responsavel pelo acionamento e gerenciamento do componente Servo 9Gç
* <AdafruitIO_WiFi.h> - Biblioteca responsavel por realizar a conexao via Wireless e tambem por conectar ao servidor AdaFruitIO, este que realiza a comunicacao via protocolo MQTT.

O acionamento remoto via protocolo MQTT foi realizado atraves do browser (Google Chrome), via site do AdafruitIO, este que disponibiliza um dashboard a ser montado conforme a demanda do projeto.

# Resultados Finais 

Após a conclusão tanto da montagem como do desenvolvimento do código, a comunicação via protocolo MQTT foi realizado com exito, mostrando que pode ser uma forma aliada nos desenvolvimentos em IoT, garantindo a execução rápida, eficaz e segura. 