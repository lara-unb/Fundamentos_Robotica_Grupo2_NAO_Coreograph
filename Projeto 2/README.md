# Projeto 2

## Introdução

Nesse projeto foi-se implementado certos modelos de rosto, de modo que o robo conseguisse por meio da percepção é da memória do rosto, corresponder ao mesmo com certas falas, utilizamos, portanto nesse projeto os sensores visuais do robô.

<p align="center">
  <img width="115" height="84" src= img21.png title="Eye Led">
  <h6 align="center">Eye Led</h6>
</p>

## Ideia
O robô irá perceber os seguintes rostos.

* Professor Raimundo
<p align="center">
  <img width="294" height="194" src= img22.png title="Raimundo head">
  <h6 align="center">Raimundo</h6>
</p>

* Iran 
<p align="center">
  <img width="187" height="105" src= img23.png title="Luva head">
  <h6 align="center">Iran</h6>
</p>

* Marcelo Rezende
<p align="center">
  <img width="186" height="152" src= img24.png title="Marcelo head">
  <h6 align="center">Marcelo</h6>
</p>

* Will Smith
<p align="center">
  <img width="163" height="116" src= img25.png title="Will head">
  <h6 align="center">Will</h6>
</p>

* Elon Musk
<p align="center">
  <img width="114" height="78" src= img26.png title="Elon head">
  <h6 align="center">Feet Wlon</h6>
</p>

Ao robô encontrar os rostos as reações/ falas são as seguintes.

* Professor Raimundo: Pergunta "Qual o salário"
* Rayan: fala "Fé em Deus pai"
* Marcelo Rezende: fala "Corta para mim"
* Will Smith: Reage com medo
* Elon Musk: fala "Olha é Elon Musk"

## Implementação

O objetivo do projeto 2 é testar a funcionalidade dos sensores dos olhos do robô NAO, é por meio disso observar a funcionalidade do mesmo se está correta é bem precisa, no decorrer do experimento as expectativas saíram de acordo com o que se erá esperado do robô NAO.

O processo de programar o robô se da do seguinte modo.

Utiliza-se o robo Learn Face sem nenhuma outra conexão no código.

<p align="center">
  <img width="127" height=107" src= img27.png title="Flow">
  <h6 align="center">Fluxo de projeto</h6>
</p>

É por meio dele se pode fazer com que o robo aprenda novos rostos, basicamente se clica em onLear no coreographe abrindo uma janela para se colocar um nome para o rosto a ser identificado, se deixa na frente da tela o rosto por alguns segundos é está pronto para se utilizar esse rosto.

Utiliza-se o bloco Face Reco. Que será responsável por fazer com que o robo analise no seu banco de rostos qual o que está presente em seu sensor, após o mesmo se manda o robo para um Switch Case que irá direcionar o robô a uma ação de acordo com o rosto observado é nomeado pelas strings dadas no Learn Face.

<p align="center">
  <img width="728" height=430" src= img20.png title="Flow">
  <h6 align="center">Fluxo de projeto</h6>
</p>

## Conclusão
Se faz notável a capacidade do robô em conseguir recolher as pessoas é responder com ações de acordo com qual pessoa que se nota, isso pode ser muito melhor abordado futuramente por meio do aprendizado de máquina para treinar algoritmos é fortalecer o robo em encontrar, por exemplo doenças em pessoas de acordo com o que o robô é capaz de perceber, ou até mesmo interagir com objetos inanimados para, por exemplo ser capaz de observar equipamentos e realizar reparos, essa interação com o ambiente é muito importante é pode ser muito mais aprimorada, dai sua importância.

## Vídeo
[Clique aqui para assistir o vídeo](https://www.youtube.com/)
