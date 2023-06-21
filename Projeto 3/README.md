# Projeto 3

## Introdução

Nesse projeto foi implementado a utilização dos sensores de áudio no robo para que por meio do mesmo fosse capaz de corresponder a comandos/falas apropriadamente.

<p align="center">
  <img width="400" height="445" src= img31.png title="Ear Right">
  <img width="400" height="445" src= img32.png title="Ear Left">
  <h6 align="center">Eye Led</h6>
</p>

## Ideia
O robô deverá responder as seguintes perguntas

* Oi
* Como vai
* Qual e o seu nome
* De onde vc é
* Quantos anos você tem
* Como foi o seu dia
* O que você faz
* Do que você gosta
* Onde você mora
* Tchau

Ao robô se deparar com as perguntas as ações implementadas foram.

* Oi : falar "Olá".
* Como vai : falar "Como robo nao tenho sentimentos".
* Qual e o seu nome : falar "Meu nome é NAO V6".
* De onde vc é : falar "Eu sou daqui mesmo".
* Quantos anos você tem : falar "Eu nao sei".
* Como foi o seu dia : falar "Foi bem".
* O que você faz : falar "Eu sou um robo".
* Do que você gosta : falar "Eu nao sei".
* Onde você mora : falar "Eu moro aqui mesmo".
* Tchau : falar "tchau".
* Caso não entender : falar "Não entendi".

## Implementação

O objetivo do projeto 3 é verificar e implementar as funcionalidades do sensor de áudio do robô NAO fazendo com que ele respondesse perguntas do dia a dia, no decorrer da implementação ocorreu o que se esperava, implementando a cara pergunta uma resposta que seria dada em seguida pelo robô.

O processo de programar o robô se deu do seguinte modo.

Utiliza-se o robo Learn Face sem nenhuma outra conexão no código.

<p align="center">
  <img width="1252" height=651" src= img30.png title="Flow">
  <h6 align="center">Fluxo de projeto</h6>
</p>

Primeiramente seguimos o Speech Reco como bloco primário do circuito ao qual o robô visualizara primeiro antes de qualquer ação, tal bloco será responsável direto por reconhecer o que o usuário disse ou quis dizer com sua pergunta, é desse modo os diálogos programados no Speech Reco são mandados para um Switch Case que será responsável por executar as ações devidas as falas do usuário, no caso quando não se houver o entendimento do robô por parte do que se foi falado então o mesmo é mandado diretamente a um bloco de fala o qual retornara dizendo que não entendeu o que foi dito.

## Conclusão
Com o avanço da sociedade algo que foi muito importante é possibilitou diversas ferramentas de auxílio ao trabalho, atividades, lazer entre outras áreas ao ser humano foi a interação entre humano é maquina, isso ocorreu por meio da melhoria da comunicação entre humanos e maquinas, o reconhecimento de fala do robô NAO tem grande importância quando se trata disso, trazendo uma possibilidade de comunicação oral entre humanos e robôs, claro que isso pode ser muito melhor ampliado é feito com inteligência artificial é aplicando outras áreas da computação e eletrônica, dai a importância do reconhecimento de fala nos robôs.

## Vídeo
[Clique aqui para assistir o vídeo](https://www.youtube.com/)
