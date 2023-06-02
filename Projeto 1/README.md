# Projeto 1

Para esse primeiro projeto o que se foi implementado, é fazer com que o robo responda com algumas reações por meio do toque em algumas partes sensiveis, desse modo foi se utilizado os sensores tateis do NAO choreographe.

<p align="center">
  <img width="340" height="269" src= img1.png title="tactile head">
  <h6 align="center">Uniform-cost search</h6>
</p>

As reações são

* Ao precionar o botão B o robo NAO vai mandar um beijo a pessoa
* Ao precionar o botão A o robo ira Olhar para cima 
* Ao precionar o botão C o robo dira olá.

O fluxo basicamente é um box do sensor tactil que executa cada uma das ações colocadas.

Ao reconhecer o toque, o robo identificara em quais partes da cabeça que se foi tocado, se foi frontTouched o mesmo é mandado ao look at que movimentara a cabeça do robo para cima, se foi na saída middleTouche então o robo executara o bloco kisses mandando um beijo a pessoa, ou se foi rearTouched o robo dirá o texto 'Olá, como vai voce'.

<p align="center">
  <img width="728" height=430" src= img2.png title="Flow">
  <h6 align="center">Uniform-cost search</h6>
</p>
