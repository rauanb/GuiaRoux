# Introdução ao Cubo Mágico
## Esquema de Cores
As cores encontradas no Cubo Mágico seguem as seguintes regras:
* **Branco** oposto ao <span style="color:#9c9720">**Amarelo**</span>
* <span style="color:red">**Vermelho**</span> oposto ao <span style="color:orange">**Laranja**</span> (cores quentes)
* <span style="color:blue">**Azul**</span> oposto ao <span style="color:green">**Verde**</span> (cores frias)
* Com <span style="color:red">**Vermelho**</span> na frente e <span style="color:#9c9720">**Amarelo**</span> em cima, à direita se tem o <span style="color:green">**Verde**</span>
  
|Esquema de Cores|
|:--:|
|<img src="cores/cores1.png" alt="drawing" width="200"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="cores/cores2.png" alt="drawing" width="200"/>|



## Peças
O cubo é formado por 3 tipos de peças, são elas:


|CENTROS: peças de 1 cor (6 no total)|
|:--:|
<img src="pecas/centros.png" alt="drawing" width="200"/>

|MEIOS: peças de 2 cores (12 no total)|
|:--:|
<img src="pecas/meios.png" alt="drawing" width="200"/>

|CANTOS: peças de 3 cores (8 no total)|
|:--:|
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

|Horário|Duplo|Anti-horário|
|:-:|:-:|:-:|
|E|E2|E'|
|<img src="moves/E/E.png" alt="drawing" width="100"/>|<img src="moves/E/E2.png" alt="drawing" width="100"/>|<img src="moves/E/Elinha.png" alt="drawing" width="100"/>|
|||
|M|M2|M'|
|<img src="moves/M/M.png" alt="drawing" width="100"/>|<img src="moves/M/M2.png" alt="drawing" width="100"/>|<img src="moves/M/Mlinha.png" alt="drawing" width="100"/>
||||
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


|**F U2 L2 B2 F' U L2 U R2 D2 L' B L2 B' R2 U2**|
|:--:|
|<img src="embaralhamento/wr0.png" alt="drawing" width="200"/>|


# Método Roux Iniciante
Inicialmente é necessário escolher uma **Orientação**, ou seja, a posição que o cubo ficará para ser resolvido. Há 24 possibilidades, e aqui será escolhida a mesma usada na seção de movimentos, ou seja, <span style="color:red">**Vermelho**</span> na frente e <span style="color:#9c9720">**Amarelo**</span> em cima. Essa orientação é a que o cubo permanecerá durante toda a solução.
## Primeiro Bloco
A primeira etapa do Método Roux é o Primeiro Bloco, do inglês First Block, simplificado para **FB**. Ele é montado na **ESQUERDA** e consiste em 6 peças, sendo 1 centro, 3 meios e 2 cantos. Considerando a orientação escolhida, o primeiro bloco será <span style="color:blue">**Azul**</span> com **Branco** embaixo. A seguir é mostrado o Primeiro Bloco. Todas as imagens dessa etapa terão o <span style="color:blue">**Azul**</span> na frente apenas para facilitar a visualização.

|Primeiro Bloco|
|:-:|
|<img src="fb/fb3.png" alt="drawing" width="200"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="fb/fb1.png" alt="drawing" width="200"/>|

Há muitas maneiras para se montar o Primeiro Bloco. A técnica utilizada aqui é focada na simplicidade e facilidade para iniciantes. Para técnicas mais avançadas, consulte a seção **Primeiro Bloco** do capítulo **Método Roux Completo**.

Inicialmente deve-se encontrar o meio (peça de duas cores) <span style="color:blue">**Azul**</span> e **Branco** e encaixar o seu <span style="color:blue">**Azul**</span> ao centro <span style="color:blue">**Azul**</span>. Algumas vezes será necessário apenas um movimento, como mostrado na figura a seguir, em que é realizado o movimento **F'**.

||F'|
|:-:|:-:|
|<img src="fb/edge/1.png" alt="drawing" width="200"/>|<img src="fb/edge/2.png" alt="drawing" width="200"/>|

Outras vezes serão necessários 2 movimentos, como mostrado na sequência **F U** a seguir.
||F|U|
|:-:|:-:|:-:|
|<img src="fb/edge/3.png" alt="drawing" width="200"/>|<img src="fb/edge/4.png" alt="drawing" width="200"/>|<img src="fb/edge/5.png" alt="drawing" width="200"/>

Após encaixar o meio <span style="color:blue">**Azul**</span> e **Branco** corretamente, o cubo deve ser colocado na que será chamda de **Posição Oficial**, que consiste em deixar o centro <span style="color:blue">**Azul**</span> na **ESQUERDA** e o **Branco** da peça <span style="color:blue">**Azul**</span> e **Branco** para baixo, como nas imagens a seguir.

|Meio Azul e Branco|
|:-:|
|<img src="fb/edge/6.png" alt="drawing" width="200"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="fb/edge/7.png" alt="drawing" width="200"/>|

Observe que agora que os movimentos D, **D'** e **D2** não podem mais ser realizados, pois iriam desfazer o que foi resolvido até o momento.

Próximo passo é encontrar o meio (peça de duas cores) <span style="color:blue">**Azul**</span> e <span style="color:red">**Vermelho**</span> ou <span style="color:blue">**Azul**</span> e <span style="color:orange">**Laranja**</span>, e levá-lo até a  **Posição de Espera**, que é a posição que está na **Frente** e **Embaixo**.
 
  A seguir é mostrado um exemplo com o meio <span style="color:blue">**Azul**</span> e <span style="color:red">**Vermelho**</span>.

||U'|M|
|:-:|:-:|:-:|
|<img src="fb/par1/1.png" alt="drawing" width="200"/>|<img src="fb/par1/2.png" alt="drawing" width="200"/>|<img src="fb/par1/3.png" alt="drawing" width="200"/>|

O meio pode estar em duas orientações possíveis, sendo ambas corretas, como mostrado a seguir.

|||
|:-:|:-:|
|<img src="fb/par1/4.png" alt="drawing" width="200"/>|<img src="fb/par1/5.png" alt="drawing" width="200"/>|

O passo seguinte é encontrar o Canto (peça de 3 cores) que faz par com a peça na **Posição de Espera**. No exemplo, o meio que está na **Posição de Espera** é <span style="color:blue">**Azul**</span> e <span style="color:red">**Vermelho**</span>, logo o canto que faz par com ela é <span style="color:blue">**Azul**</span> e <span style="color:red">**Vermelho**</span> e **Branco**. Esse canto deve ser levado até a camada de cima, com o seu **Branco** para o lado **DIREITO** OU **ESQUERDO**


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