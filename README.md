# Introdução ao Cubo Mágico
## Esquema de Cores
As cores encontradas no Cubo Mágico seguem as seguintes regras:
* **Branco** oposto ao <span style="color:#9c9720">**Amarelo**</span>
* <span style="color:red">**Vermelho**</span> oposto ao <span style="color:orange">**Laranja**</span> (cores quentes)
* <span style="color:blue">**Azul**</span> oposto ao <span style="color:green">**Verde**</span> (cores frias)
* Com <span style="color:red">**Vermelho**</span> na frente e <span style="color:#9c9720">**Amarelo**</span> em cima, à direita se tem o <span style="color:green">**Verde**</span>

<img src="cores/cores1.png" alt="drawing" width="200"/><img src="cores/cores2.png" alt="drawing" width="200"/>



## Peças
O cubo é formado por 3 tipos de peças, são elas:
* **Centros:** peças de 1 cor, sendo 6 no total

<img src="pecas/centros.png" alt="drawing" width="200"/>

* **Meios:** peças de 2 cores, sendo 12 no total

<img src="pecas/meios.png" alt="drawing" width="200"/>

* **Cantos:** peças de 3 cores, sendo 8 no total

<img src="pecas/cantos.png" alt="drawing" width="200"/>

## Como Resolver
Ao contrário do senso comum, não existe somente uma forma para se resolver o Cubo Mágico. Existem alguns métodos, e nesse material será explicado o método **Roux**

## Movimentos do Cubo
Para aprender qualquer método é necessário saber movimentar as peças do Cubo. Abaixo são mostrados os movimentos, considerando o **Cubo resolvido**, com  a face <span style="color:red">**Vermelha**</span> na frente e a <span style="color:#9c9720">**Amarela**</span> em cima.


|Horário|Duplo|Anti-horário|Amplo Horário|Amplo Duplo|Amplo Anti-horário
|:-:|:-:|:-:|:-:|:-:|:-:|
|B|B2|B'|Bw|Bw2|Bw' 
|<img src="moves/B/B.png" alt="drawing" width="100"/>|<img src="moves/B/B2.png" alt="drawing" width="100"/>|<img src="moves/B/Blinha.png" alt="drawing" width="100"/>|<img src="moves/B/b.png" alt="drawing" width="100"/>|<img src="moves/B/b2.png" alt="drawing" width="100"/>|<img src="moves/B/blinha.png" alt="drawing" width="90"/>
|||||||
|D|D2|D'|Dw|Dw2|Dw' 
|<img src="moves/D/D.png" alt="drawing" width="100"/>|<img src="moves/D/D2.png" alt="drawing" width="100"/>|<img src="moves/D/Dlinha.png" alt="drawing" width="100"/>|<img src="moves/D/d.png" alt="drawing" width="100"/>|<img src="moves/D/d2.png" alt="drawing" width="100"/>|<img src="moves/D/dlinha.png" alt="drawing" width="90"/>
|||||||
|F|F2|F'|Fw|Fw2|Fw' 
|<img src="moves/F/F.png" alt="drawing" width="100"/>|<img src="moves/F/F2.png" alt="drawing" width="100"/>|<img src="moves/F/Flinha.png" alt="drawing" width="100"/>|<img src="moves/F/f.png" alt="drawing" width="100"/>|<img src="moves/F/f2.png" alt="drawing" width="100"/>|<img src="moves/F/flinha.png" alt="drawing" width="90"/>
|||||||
|L|L2|L'|Lw|Lw2|Lw' 
|<img src="moves/L/L.png" alt="drawing" width="100"/>|<img src="moves/L/L2.png" alt="drawing" width="100"/>|<img src="moves/L/Llinha.png" alt="drawing" width="100"/>|<img src="moves/L/l.png" alt="drawing" width="100"/>|<img src="moves/L/l2.png" alt="drawing" width="100"/>|<img src="moves/L/llinha.png" alt="drawing" width="90"/>
|||||||
|R|R2|R'|Rw|Rw2|Rw' 
|<img src="moves/R/R.png" alt="drawing" width="100"/>|<img src="moves/R/R2.png" alt="drawing" width="100"/>|<img src="moves/R/Rlinha.png" alt="drawing" width="100"/>|<img src="moves/R/r.png" alt="drawing" width="100"/>|<img src="moves/R/r2.png" alt="drawing" width="100"/>|<img src="moves/R/rlinha.png" alt="drawing" width="90"/>
|||||||
|U|U2|U'|Uw|Uw2|Uw' 
|<img src="moves/U/U.png" alt="drawing" width="100"/>|<img src="moves/U/U2.png" alt="drawing" width="100"/>|<img src="moves/U/Ulinha.png" alt="drawing" width="100"/>|<img src="moves/U/u.png" alt="drawing" width="100"/>|<img src="moves/U/u2.png" alt="drawing" width="100"/>|<img src="moves/U/ulinha.png" alt="drawing" width="90"/>
|||||||
|E|E2|E'|||
|<img src="moves/E/E.png" alt="drawing" width="100"/>|<img src="moves/E/E2.png" alt="drawing" width="100"/>|<img src="moves/E/Elinha.png" alt="drawing" width="100"/>|
|||||||
|M|M2|M'||| 
|<img src="moves/M/M.png" alt="drawing" width="100"/>|<img src="moves/M/M2.png" alt="drawing" width="100"/>|<img src="moves/M/Mlinha.png" alt="drawing" width="100"/>
|||||||
|S|S2|S'|||
|<img src="moves/S/S.png" alt="drawing" width="100"/>|<img src="moves/S/S2.png" alt="drawing" width="100"/>|<img src="moves/S/Slinha.png" alt="drawing" width="100"/>
|||||||
|x|x2|x'||| 
|<img src="moves/Eixos/X.png" alt="drawing" width="100"/>|<img src="moves/Eixos/X2.png" alt="drawing" width="100"/>|<img src="moves/Eixos/Xlinha.png" alt="drawing" width="100"/>
|||||||
|y|y2|y'||| 
|<img src="moves/Eixos/Y.png" alt="drawing" width="100"/>|<img src="moves/Eixos/Y2.png" alt="drawing" width="100"/>|<img src="moves/Eixos/Ylinha.png" alt="drawing" width="100"/>
|z|z2|z'|||
|<img src="moves/Eixos/Z.png" alt="drawing" width="100"/>|<img src="moves/Eixos/Z2.png" alt="drawing" width="100"/>|<img src="moves/Eixos/Zlinha.png" alt="drawing" width="100"/>

A título de exemplo, é mostrada a seguir a fórmula **Sune**, movimento a movimento, aplicada com o **Cubo resolvido**.

||R|U|R'|U|R|U2|R'
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|<img src="moves/Sune/0.png" alt="drawing" width="100"/>|<img src="moves/Sune/1.png" alt="drawing" width="100"/>|<img src="moves/Sune/2.png" alt="drawing" width="100"/>|<img src="moves/Sune/3.png" alt="drawing" width="100"/>|<img src="moves/Sune/4.png" alt="drawing" width="100"/>|<img src="moves/Sune/5.png" alt="drawing" width="100"/>|<img src="moves/Sune/6.png" alt="drawing" width="100"/>|<img src="moves/Sune/7.png" alt="drawing" width="100"/>

## Como Embaralhar
Para embaralhar, segundo as orientações da **World Cube Association** (WCA), o **Cubo resolvido** deve ser orientado com a face <span style="color:green">**Verde**</span> na frente e a **Branca** em cima. A seguir é mostrado o Cubo após realizado o seguinte embaralhamento:

**F U2 L2 B2 F' U L2 U R2 D2 L' B L2 B' R2 U2**

<img src="embaralhamento/wr0.png" alt="drawing" width="200"/>

# Método Roux Iniciante
Inicialmente é necessário escolher uma **Orientação**, ou seja, a posição que o cubo ficará para ser resolvido. Há 24 possibilidades, e aqui será escolhida a mesma usada na seção de movimentos, ou seja, <span style="color:red">**Vermelho**</span> na frente e <span style="color:#9c9720">**Amarelo**</span> em cima. Essa orientação é a que o cubo permanecerá durante toda a solução.
## Primeiro Bloco
A primeira etapa do Método Roux é o Primeiro Bloco, do inglês First Block, simplificado para **FB**. Ele é montado na **ESQUERDA** e consiste em 6 peças, sendo 1 centro, 3 meios e 2 cantos. Considerando a orientação escolhida, o primeiro bloco será <span style="color:blue">**Azul**</span> com **Branco** embaixo. A seguir é mostrado o Primeiro Bloco. Observe que na primeira imagem o Cubo é mostrado com o <span style="color:blue">**Azul**</span> na frente apenas para facilitar a visualização.

<img src="fb/fb3.png" alt="drawing" width="200"/> <img src="fb/fb1.png" alt="drawing" width="200"/>

Há muitas maneiras para se montar o Primeiro Bloco. A técnica utilizada aqui é focada na simplicidade e facilidade para iniciantes. Para ténicas mais avançadas consultar seção **Primeiro Bloco** do capítulo **Método Roux Completo**.

Inicialmente deve-se posicionar o centro <span style="color:blue">**Azul**</span> na **ESQUERDA**, o que coloca o centro <span style="color:green">**Verde**</span> na **DIREITA**

<img src="fb/centro1.png" alt="drawing" width="200"/> <img src="fb/centro2.png" alt="drawing" width="200"/>

A seguir deve-se encontrar o meio (peça de duas cores) <span style="color:blue">**Azul**</span> e **Branco** e encaixar o seu <span style="color:blue">**Azul**</span> ao centro <span style="color:blue">**Azul**</span>

# Método Roux Completo
## Neutralidade de cor
## Primeiro Bloco
### Meio + Pares
### Meia Linha + Par
### Linhas

# Tópicos Avançados
## EOLR
## 
## UFUB
## Pinkie Pie