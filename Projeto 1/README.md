# Projeto 1

## Introdução

Para esse primeiro projeto o que se foi implementado, é fazer com que o robô responda com algumas reações por meio do toque em partes sensíveis, desse modo foi se utilizado os sensores táteis do NAO choreographe.

## Ideia
Um dos primeiros sensores a serem utilizados é o sensor da cabeça, onde contém três partes sensíveis mostradas abaixo.

<p align="center">
  <img width="340" height="269" src= img1.png title="tactile head">
  <h6 align="center">Tactile Head</h6>
</p>

Ao se perceber o toque na cabeça o NAO realiza as seguintes reações:

* Ao pressionar o botão B o robô NAO vai mandar um beijo a pessoa.
* Ao pressionar o botão A o robo ira Olhar para cima.
* Ao pressionar o botão C o robô dirá olá.

<p align="center">
  <img width="259" height="210" src= img2.png title="tactile head">
  <h6 align="center">Chest Button</h6>
</p>

Sobre o sensor do peito, não se foi implementado nenhuma animação para o NAO.

<p align="center">
  <img width="581" height="228" src= img3.png title="tactile head">
  <h6 align="center">Tactile Hands</h6>
</p>

Ao se encostar nas mãos o não reproduz as seguintes reações.
* Sobre a mão esquerda ao ser tocado tanto na parte esquerda, na direita ou na central, o NAO reconhecera o toque é realizara gesticulação de felicidade.
* Sobre a mão direita o mesmo realiza uma ação de curiosidade.

<p align="center">
  <img width="310" height="211" src= img4.png title="tactile head">
  <h6 align="center">Feet Bumpers</h6>
</p>

Ao se encostar nos pés o não reproduz as seguintes reações.
* Irá interagir com o usuário por meio de falar, ao ser pressionado o sensor é voltará a posição original ao se soltar.

## Implementação
O fluxo basicamente é um box do sensor táctil que executa cada uma das ações colocadas.

Ao reconhecer o toque, o robô identificara em quais partes do seu corpo que se foi acionado o toque, a depender de qual parte do corpo o mesmo se foi acionado na Tactile ao se tocar a frontTouched o robô ira fazer a animação de olhar para frente, ao se tocar middleTouched o robô realiza a ação de mandar um beijo é ao se tocar rearTouched o mesmo interagi por fala com o usuário, ao se tocar em qualquer uma das partes da mão direita o mesmo realiza uma interação de felicidade é na mão direita uma reação de curiosidade, é sobre os pés a depender de pressionar o sensor o robô realiza uma ação de curiosidade.

<p align="center">
  <img width="802" height=593" src= img5.png title="Flow">
  <h6 align="center">Fluxo de projeto</h6>
</p>

A implementação se dá do seguinte modo, todos os sensores são ativados por meio da ligação entre os blocos sensores é o início, o bloco Tactile R.Hand controle as três partes da mão direita por meio dos sensores mostrados é estão todas as partes ligadas ao mesmo bloco o bloco Tactile L.Hand controla as ações da mão esquerda é por meio desse colocamos a ação desejada de curiosidade é assim se prossegue para os blocos Tactile Head é Foot Contact que coordenaram respectivamente a cabela é os pés, é por meio desses somos capazes de verificar a funcionalidade dos sensores.

## Conclusão 
Como vemos durante a implementação e experimentação dos sensores tácteis é possível aproximar o ser humano a ações que ele poderia vir a ter de acordo com a zona tocada, aí está uma das importâncias dos sensores táteis para a robótica.

## Vídeos
[Clique aqui para assistir o vídeo](https://www.youtube.com/)
