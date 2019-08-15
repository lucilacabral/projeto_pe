# PROJETO FINAL DA DISCIPLINA DE TÉCNICAS DE PROGRAMAÇÃO
# ALUNOS: LOAN MATTEUS (20182610039) E LUCILA MARIA(20182610035)

TERMOHIDRO é o projeto de uma front-end de uma aplicação que monitora a temperatura de piscinas de um Centro de Terapia e Reabilitação por meio da hidroterapia em piscinas aquecidas. Foi feito utilizando o QT Creator, Heroku e NodeMCU Esp8266 para a disciplina de Técnicas de Programaão.

TERMOHIDRO permitirá qu o funcionário monitore a temperatura das piscinas em tempo real com o auxílio do site criado com o HerokuAPP, e do QT Creator escolha a porta e a velocidade para se conectar a NodeMCU. Dessa forma verifica se o animal está pronto para ser doado.

### Em HTML
##### Tela Principal do Projeto
![Index.html1](/imgs/Index-Piscinas.png "Piscinas")

##### Tela de Conexão
![Index.html2](/imgs/Conexao.png "Conexao")

### Em QTCreator
##### Principal
![MainWindow1](/imgs/MainWindow-Piscina.png "Piscinas")

##### Conexão
![MainWindow2](/imgs/MainWindow-Conexao.png "Conexao")

## Circuito

Em teoria o sensor de tempera deveria calcular e enviar por um arquivo .json para uma APIRest feita no servidor para que o mesmo enviar o dado da temperatura medida no sensor e poder ser mostrado em cada aplicação (Tanto Web em HTML quando Desktop feito pelo QTCreator).

### Circuito do Sensor
![Sensor](/imgs/circuito.png "Sensor/Circuito")
