# PROJETO FINAL DA DISCIPLINA DE TÉCNICAS DE PROGRAMAÇÃO
## ALUNOS: LOAN MATTEUS (20182610039) E LUCILA MARIA(20182610035)

TERMOHIDRO é o projeto de uma front-end de uma aplicação que monitora a temperatura de piscinas de um Centro de Terapia e Reabilitação por meio da hidroterapia em piscinas aquecidas. Foi feito utilizando o QT Creator, Heroku e NodeMCU Esp8266 para a disciplina de Técnicas de Programaão.

TERMOHIDRO permitirá qu o funcionário monitore a temperatura das piscinas em tempo real com o auxílio do site criado com o HerokuAPP que é a forma de conexão online do funcionário, e do QT Creator que é a forma de conexão offline do funcionário.

##### Tela Principal do Projeto
![Index.html1](/imgs/Index-Piscinas.png "Piscinas")

Na tela principal do site, o funcionário poderá ver em tempo tempo real a temperatura das piscinas e selecionar a piscina que deseja ocupar. Ao clicar no botão 'OCUPAR' o símbolo cinza passará a ser vermelho.

##### Tela de Conexão
![Index.html2](/imgs/Conexao.png "Conexao")

Na tela de conexão do site, o funcionário deve selecionar a porta a velocidade de conexão com a placa e será capaz de ver o status da conexão com a NodeMCU. "Conectado", caso a comunicação com a NodeMCU tenha sido efetuada, ou "desconectado", caso não. Dessa forma, poderá ver a temperatura na tela principal. 

### Em QTCreator
##### Principal
![MainWindow1](/imgs/MainWindow-Piscina.png "Piscinas")

Na tela principal da aplicação no QT Creator o funcionário poderá selecionar a piscina que deseja ocupar ou desocupar. A temperatura de cada uma aparecerá em tempo real abaixo do número de cada piscina, após a conexão com a placa ser feita na aba de conexão da aplicação.

##### Conexão
![MainWindow2](/imgs/MainWindow-Conexao.png "Conexao")

Na tela de conexão do QT Creator, o funcionário poderá selecionar a porta e a velocidade de conexão com a NodeMCU.

## Circuito

Em teoria o sensor de tempera deveria calcular e enviar por um arquivo .json para uma APIRest feita no servidor para que o mesmo enviar o dado da temperatura medida no sensor e poder ser mostrado em cada aplicação (Tanto Web em HTML quando Desktop feito pelo QTCreator).

### Circuito do Sensor
![Sensor](/imgs/circuito.png "Sensor/Circuito")
