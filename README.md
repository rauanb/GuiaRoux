# Introdução ao Cubo Mágico
## Esquema de Cores
As cores encontradas no Cubo Mágico seguem as seguintes regras:
* **Branco** oposto ao <span style="color:#9c9720">**Amarelo**</span>
* <span style="color:red">**Vermelho**</span> oposto ao <span style="color:orange">**Laranja**</span> (cores quentes)
* <span style="color:blue">**Azul**</span> oposto ao <span style="color:green">**Verde**</span> (cores frias)
* Com <span style="color:red">**Vermelho**</span> na frente e <span style="color:#9c9720">**Amarelo**</span> em cima, a direita se tem o <span style="color:green">**Verde**</span>
  
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
Ao contrário do senso comum, não existe somente uma forma para se resolver o Cubo Mágico. Existem alguns métodos, e nesse material será explicado o método **Roux**.

## Movimentos do Cubo
Para aprender qualquer método é necessário saber movimentar as peças do Cubo. Abaixo são mostrados os movimentos, considerando o **Cubo resolvido**, com  a face <span style="color:red">**Vermelha**</span> na frente e a <span style="color:#9c9720">**Amarela**</span> em cima.


|Horário|Duplo|Anti-horário|Amplo Horário|Amplo Duplo|Amplo Anti-horário|
|:-:|:-:|:-:|:-:|:-:|:-:|
|B|B2|B'|Bw|Bw2|Bw' |
|<img src="moves/B/B.png" alt="drawing" width="100"/>|<img src="moves/B/B2.png" alt="drawing" width="100"/>|<img src="moves/B/Blinha.png" alt="drawing" width="100"/>|<img src="moves/B/b.png" alt="drawing" width="100"/>|<img src="moves/B/b2.png" alt="drawing" width="100"/>|<img src="moves/B/blinha.png" alt="drawing" width="100"/>|
|||||||
|D|D2|D'|Dw|Dw2|Dw' |
|<img src="moves/D/D.png" alt="drawing" width="100"/>|<img src="moves/D/D2.png" alt="drawing" width="100"/>|<img src="moves/D/Dlinha.png" alt="drawing" width="100"/>|<img src="moves/D/d.png" alt="drawing" width="100"/>|<img src="moves/D/d2.png" alt="drawing" width="100"/>|<img src="moves/D/dlinha.png" alt="drawing" width="100"/>|
|||||||
|F|F2|F'|Fw|Fw2|Fw' |
|<img src="moves/F/F.png" alt="drawing" width="100"/>|<img src="moves/F/F2.png" alt="drawing" width="100"/>|<img src="moves/F/Flinha.png" alt="drawing" width="100"/>|<img src="moves/F/f.png" alt="drawing" width="100"/>|<img src="moves/F/f2.png" alt="drawing" width="100"/>|<img src="moves/F/flinha.png" alt="drawing" width="100"/>|
|||||||
|L|L2|L'|Lw|Lw2|Lw' |
|<img src="moves/L/L.png" alt="drawing" width="100"/>|<img src="moves/L/L2.png" alt="drawing" width="100"/>|<img src="moves/L/Llinha.png" alt="drawing" width="100"/>|<img src="moves/L/l.png" alt="drawing" width="100"/>|<img src="moves/L/l2.png" alt="drawing" width="100"/>|<img src="moves/L/llinha.png" alt="drawing" width="100"/>|
|||||||
|R|R2|R'|Rw|Rw2|Rw' |
|<img src="moves/R/R.png" alt="drawing" width="100"/>|<img src="moves/R/R2.png" alt="drawing" width="100"/>|<img src="moves/R/Rlinha.png" alt="drawing" width="100"/>|<img src="moves/R/r.png" alt="drawing" width="100"/>|<img src="moves/R/r2.png" alt="drawing" width="100"/>|<img src="moves/R/rlinha.png" alt="drawing" width="100"/>|
|||||||
|U|U2|U'|Uw|Uw2|Uw' |
|<img src="moves/U/U.png" alt="drawing" width="100"/>|<img src="moves/U/U2.png" alt="drawing" width="100"/>|<img src="moves/U/Ulinha.png" alt="drawing" width="100"/>|<img src="moves/U/u.png" alt="drawing" width="100"/>|<img src="moves/U/u2.png" alt="drawing" width="100"/>|<img src="moves/U/ulinha.png" alt="drawing" width="100"/>|

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

|Exemplo|R|U|R'|U|R|U2|R'
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
A primeira etapa do Método Roux é o Primeiro Bloco, do inglês First Block, simplificado para **FB**. Ele é montado na **ESQUERDA** e consiste em 6 peças, sendo 1 centro, 3 meios e 2 cantos. Considerando a orientação escolhida, o primeiro bloco será <span style="color:blue">**Azul**</span> com **Branco** embaixo. A seguir é mostrado o Primeiro Bloco. Algumas imagens dessa etapa terão o <span style="color:blue">**Azul**</span> na frente apenas para facilitar a visualização.

|Primeiro Bloco|
|:-:|
|<img src="fb/fb3.png" alt="drawing" width="200"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="fb/fb1.png" alt="drawing" width="200"/>|

Há muitas maneiras para se montar o Primeiro Bloco. A técnica utilizada aqui é focada na simplicidade e facilidade para iniciantes. Para técnicas mais avançadas, consulte a seção **Primeiro Bloco** do capítulo **Método Roux Completo**.

Inicialmente deve-se encontrar o meio (peça de duas cores) <span style="color:blue">**Azul**</span> e **Branco** e encaixar o seu <span style="color:blue">**Azul**</span> ao centro <span style="color:blue">**Azul**</span>.

**Algumas vezes será necessário apenas um movimento, como no exemplo abaixo.**

|Exemplo|F'|
|:-:|:-:|
|<img src="fb/edge/1.png" alt="drawing" width="200"/>|<img src="fb/edge/2.png" alt="drawing" width="200"/>|

Outras vezes serão necessários 2 movimentos, como no exemplo.
|Exemplo|F|U|
|:-:|:-:|:-:|
|<img src="fb/edge/3.png" alt="drawing" width="200"/>|<img src="fb/edge/4.png" alt="drawing" width="200"/>|<img src="fb/edge/5.png" alt="drawing" width="200"/>

Após encaixar o meio <span style="color:blue">**Azul**</span> e **Branco** corretamente, o cubo deve ser colocado na que será chamda de **Posição Oficial**, que consiste em deixar o centro <span style="color:blue">**Azul**</span> na **ESQUERDA** e o **Branco** da peça <span style="color:blue">**Azul**</span> e **Branco** para baixo, como nas imagens a seguir.

|Meio Azul e Branco|
|:-:|
|<img src="fb/edge/6.png" alt="drawing" width="200"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="fb/edge/7.png" alt="drawing" width="200"/>|

**MOVIMENTOS PROIBIDOS:** As camadas **D** e **L** não podem mais ser mexidas.

Lembrando que, ao posicionar o cubo, o centro <span style="color:green">**Verde**</span> ficará na **DIREITA**, pois ele é oposto ao <span style="color:blue">**Azul**</span>.

Próximo passo é encontrar o meio (peça de duas cores) <span style="color:blue">**Azul**</span> e <span style="color:red">**Vermelho**</span> e levá-lo até a  **Posição de Espera**, que é a posição que está na **Frente** e **Embaixo**, como no exemplo.

|Exemplo|U'|M|
|:-:|:-:|:-:|
|<img src="fb/par1/1.png" alt="drawing" width="200"/>|<img src="fb/par1/2.png" alt="drawing" width="200"/>|<img src="fb/par1/3.png" alt="drawing" width="200"/>|

O meio pode estar em duas orientações possíveis, sendo ambas corretas.

|||
|:-:|:-:|
|<img src="fb/par1/4.png" alt="drawing" width="200"/>|<img src="fb/par1/5.png" alt="drawing" width="200"/>|

O passo seguinte é encontrar o canto (peça de 3 cores) que faz par com a peça na **Posição de Espera**, que é o <span style="color:blue">**Azul**</span>, <span style="color:red">**Vermelho**</span> e **Branco**. Leve esse canto para a camada de cima, de forma que o seu **Branco** fique para a **DIREITA** OU para a **ESQUERDA**.

Abaixo é mostrado um caso que precisa de atenção, pois o canto está na posição **FDL**, ou seja, na **FRENTE** **EMBAIXO** na **ESQUERDA**.

|Exemplo|L'|U'|L|
|:-:|:-:|:-:|:-:|
|<img src="fb/par1/16.png" alt="drawing" width="200"/>|<img src="fb/par1/17.png" alt="drawing" width="200"/>|<img src="fb/par1/18.png" alt="drawing" width="200"/>|<img src="fb/par1/19.png" alt="drawing" width="200"/>|

Se o **Branco** estiver para cima:
* Levar o canto para a posição na **DIREITA ATRÁS** girando a camada de **CIMA**
* Girar a direita no sentido anti-horário
* Girar a camada de cima no sentido horário



|Exemplo|U'|R'|U|
|:-:|:-:|:-:|:-:|
|<img src="fb/par1/6.png" alt="drawing" width="200"/>|<img src="fb/par1/7.png" alt="drawing" width="200"/>|<img src="fb/par1/8.png" alt="drawing" width="200"/>|<img src="fb/par1/9.png" alt="drawing" width="200"/>|<img src="fb/par1/9.png" alt="drawing" width="200"/>|

O passo seguinte é formar o par, levando o meio que está na **posição de espera** até o canto, girando a camada **M**.

|Exemplo|M'||
|:-:|:-:|:-:|
|<img src="fb/par1/9.png" alt="drawing" width="200"/>|<img src="fb/par1/10.png" alt="drawing" width="200"/>|<img src="fb/par1/20.png" alt="drawing" width="200"/>|

Caso o par fique com as cores trocadas:
* Voltar o meio para a posição de espera
* Girar a camada de **CIMA** 2 vezes
* Formar o par novamente na nova posição

|Exemplo|M|U2|M2|
|:-:|:-:|:-:|:-:|
|<img src="fb/par1/11.png" alt="drawing" width="200"/>|<img src="fb/par1/12.png" alt="drawing" width="200"/>|<img src="fb/par1/13.png" alt="drawing" width="200"/>|<img src="fb/par1/15.png" alt="drawing" width="200"/>|

Depois de formar o par, ele deve ser posicionado na **FRENTE** e encaixado, com uma das formas a seguir.

|Exemplo|F'|
|:-:|:-:|
|<img src="fb/par1/20.png" alt="drawing" width="200"/>|<img src="fb/par1/21.png" alt="drawing" width="200"/>|

|Exemplo|Rw'|F|
|:-:|:-:|:-:|
|<img src="fb/par1/22.png" alt="drawing" width="200"/>|<img src="fb/par1/23.png" alt="drawing" width="200"/>|<img src="fb/par1/21.png" alt="drawing" width="200"/>|

**MOVIMENTOS PROIBIDOS:** As camadas **D**, **L** e **F** não podem mais ser mexidas.

O mesmo processo vai ser feito para o par de trás, que é o <span style="color:blue">**Azul**</span> e <span style="color:orange">**Laranja**</span>:
* O meio <span style="color:blue">**Azul**</span> e <span style="color:orange">**Laranja**</span> deve ser levado até a **Posição de Espera**

|Exemplo|B'|M2|
|:-:|:-:|:-:|
|<img src="fb/par2/0.png" alt="drawing" width="200"/>|<img src="fb/par2/1.png" alt="drawing" width="200"/>|<img src="fb/par2/2.png" alt="drawing" width="200"/>|
* O canto <span style="color:blue">**Azul**</span>, <span style="color:orange">**Laranja**</span> e **Branco** deve ser colocado na camada de **CIMA** com o **Branco** para a **Direita** ou **Esquerda**.

|Exemplo||R|U'|
|:-:|:-:|:-:|:-:|
|<img src="fb/par2/3.png" alt="drawing" width="200"/>|<img src="fb/par2/4.png" alt="drawing" width="200"/>|<img src="fb/par2/5.png" alt="drawing" width="200"/>|<img src="fb/par2/6.png" alt="drawing" width="200"/>|
* O par deve ser formado usando **M'** ou **M2**, posicionado e encaixado **ATRÁS**. 

|Exemplo|M2||Rw|B'|
|:-:|:-:|:-:|:-:|:-:|
|<img src="fb/par2/6.png" alt="drawing" width="200"/>|<img src="fb/par2/7.png" alt="drawing" width="200"/>|<img src="fb/par2/8.png" alt="drawing" width="200"/>|<img src="fb/par2/9.png" alt="drawing" width="200"/>|<img src="fb/par2/10.png" alt="drawing" width="200"/>|

|Exemplo|B|
|:-:|:-:|
|<img src="fb/par2/11.png" alt="drawing" width="200"/>|<img src="fb/fb3.png" alt="drawing" width="200"/>|

## Segundo Bloco

A segunda etapa do Método Roux é o Segundo Bloco, do inglês Second Block, simplificado para **SB**. Ele é montado na **DIREITA** e consiste em 6 peças, sendo 1 centro, 3 meios e 2 cantos. Considerando a orientação escolhida, o segundo bloco será <span style="color:green">**Verde**</span> com **Branco** embaixo.

|Segundo Bloco|
|:-:|
|<img src="sb/sb.png" alt="drawing" width="200"/>|

As mesmas etapas do **FB** serão aplicadas aqui:
* Encaixar o meio <span style="color:green">**Verde**</span> e **Branco**

|Exemplo|R|U|M'|U|R2|
|:-:|:-:|:-:|:-:|:-:|:-:|
|<img src="sb/edge/1.png" alt="drawing" width="200"/>|<img src="sb/edge/2.png" alt="drawing" width="200"/>|<img src="sb/edge/3.png" alt="drawing" width="200"/>|<img src="sb/edge/4.png" alt="drawing" width="200"/>|<img src="sb/edge/5.png" alt="drawing" width="200"/>|<img src="sb/edge/6.png" alt="drawing" width="200"/>|

* Colocar o meio <span style="color:green">**Verde**</span> e <span style="color:red">**Vermelho**</span> na posição de espera


|Exemplo|R|U|Rw'|
|:-:|:-:|:-:|:-:|
|<img src="sb/par1/1.png" alt="drawing" width="200"/>|<img src="sb/par1/2.png" alt="drawing" width="200"/>|<img src="sb/par1/3.png" alt="drawing" width="200"/>|<img src="sb/par1/4.png" alt="drawing" width="200"/>|


* Colocar o canto <span style="color:green">**Verde**</span>, <span style="color:red">**Vermelho**</span> e **Branco** na camada de cima, com o **Branco** para a **DIREITA** ou **ESQUERDA**. Atenção para voltar o meio <span style="color:green">**Verde**</span> e <span style="color:red">**Vermelho**</span> para **BAIXO**.

|Exemplo|R|U2|R'|
|:-:|:-:|:-:|:-:|
|<img src="sb/par1/5.png" alt="drawing" width="200"/>|<img src="sb/par1/6.png" alt="drawing" width="200"/>|<img src="sb/par1/7.png" alt="drawing" width="200"/>|<img src="sb/par1/8.png" alt="drawing" width="200"/>|
* Formar o par e encaixar com uma das formas a seguir.

|Exemplo|M2|U2|Rw|U|R'|
|:-:|:-:|:-:|:-:|:-:|:-:|
|<img src="sb/par1/8.png" alt="drawing" width="200"/>|<img src="sb/par1/9.png" alt="drawing" width="200"/>|<img src="sb/par1/10.png" alt="drawing" width="200"/>|<img src="sb/par1/11.png" alt="drawing" width="200"/>|<img src="sb/par1/12.png" alt="drawing" width="200"/>|<img src="sb/par1/13.png" alt="drawing" width="200"/>|

|Exemplo|R|U'|R'|
|:-:|:-:|:-:|:-:|
|<img src="sb/par1/14.png" alt="drawing" width="200"/>|<img src="sb/par1/15.png" alt="drawing" width="200"/>|<img src="sb/par1/12.png" alt="drawing" width="200"/>|<img src="sb/par1/13.png" alt="drawing" width="200"/>|

* Colocar o meio <span style="color:green">**Verde**</span> e <span style="color:orange">**Laranja**</span> na posição de espera

|Exemplo|R'|U|R|M|
|:-:|:-:|:-:|:-:|:-:|
|<img src="sb/par2/1.png" alt="drawing" width="200"/>|<img src="sb/par2/2.png" alt="drawing" width="200"/>|<img src="sb/par2/3.png" alt="drawing" width="200"/>|<img src="sb/par2/4.png" alt="drawing" width="200"/>|<img src="sb/par2/5.png" alt="drawing" width="200"/>|

* Colocar o canto <span style="color:green">**Verde**</span>, <span style="color:orange">**Laranja**</span> e **Branco** na camada de cima, com o **Branco** para a **DIREITA** ou **ESQUERDA**. Atenção para voltar o meio <span style="color:green">**Verde**</span> e <span style="color:red">**Vermelho**</span> para **BAIXO**.

|Exemplo|U'|R'|U|R|
|:-:|:-:|:-:|:-:|:-:|
|<img src="sb/par2/6.png" alt="drawing" width="200"/>|<img src="sb/par2/7.png" alt="drawing" width="200"/>|<img src="sb/par2/8.png" alt="drawing" width="200"/>|<img src="sb/par2/9.png" alt="drawing" width="200"/>|<img src="sb/par2/10.png" alt="drawing" width="200"/>|

* Formar o par e encaixar usando uma das formas a seguir.

|Exemplo|M'|U2|Rw'|U'|R|
|:-:|:-:|:-:|:-:|:-:|:-:|
|<img src="sb/par2/10.png" alt="drawing" width="200"/>|<img src="sb/par2/11.png" alt="drawing" width="200"/>|<img src="sb/par2/12.png" alt="drawing" width="200"/>|<img src="sb/par2/13.png" alt="drawing" width="200"/>|<img src="sb/par2/14.png" alt="drawing" width="200"/>|<img src="sb/par2/15.png" alt="drawing" width="200"/>|

|Exemplo|M'|U2|R'|U|R|
|:-:|:-:|:-:|:-:|:-:|:-:|
|<img src="sb/par2/16.png" alt="drawing" width="200"/>|<img src="sb/par2/17.png" alt="drawing" width="200"/>|<img src="sb/par2/18.png" alt="drawing" width="200"/>|<img src="sb/par2/19.png" alt="drawing" width="200"/>|<img src="sb/par2/20.png" alt="drawing" width="200"/>|<img src="sb/par2/15.png" alt="drawing" width="200"/>|

## Orientação dos Cantos (CMLL 1/2)

Nessa etapa os cantos da camada de **CIMA** terão o seu <span style="color:#9c9720">**Amarelo**</span> jogado para **CIMA**. Para isso será usada a fórmula **SUNE**, que foi comentada na seção de **Movimentos do Cubo**. Seu efeito no cubo é "torcer" o canto **DIREITO** da **FRENTE**  e os de **TRÁS** no sentido **HORÁRIO**.

|                       Sune                        |                         R                         |                         U                         |                        R'                         |                         U                         |                         R                         |                        U2                         |                        R'                         |
| :-----------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------------: |
| <img src="Sune/1.png" alt="drawing" width="200"/> | <img src="Sune/2.png" alt="drawing" width="200"/> | <img src="Sune/3.png" alt="drawing" width="200"/> | <img src="Sune/4.png" alt="drawing" width="200"/> | <img src="Sune/5.png" alt="drawing" width="200"/> | <img src="Sune/6.png" alt="drawing" width="200"/> | <img src="Sune/7.png" alt="drawing" width="200"/> | <img src="Sune/8.png" alt="drawing" width="200"/> |

Sabendo disso, é necessário escolher qual posição da camada de **CIMA** o **SUNE** vai ser aplicado. Basta seguir as regras:

1. Se houver somente 1 <span style="color:#9c9720">**Amarelo**</span> para **CIMA**, levá-lo até a **ESQUERDA** na **FRENTE** e fazer o **SUNE**.

2. Se não, verificar se ao "torcer", no sentido horário, o canto da **DIREITA** na **FRENTE** e os de **TRÁS**, ficará somente 1 amarelo para **CIMA**.

   2A. Se sim, fazer o **SUNE** nessa posição, o resultado vai ser o caso **1** acima.

   2B. Se não, façzero movimento **U** e verificar novamente o caso **2** acima.

Seguindo as regras acima, o número máximo de vezes que será preciso fazer o **SUNE** é 3.

Abaixo são mostradas as 7 orientações possíveis, juntamente com a sua posição correta para se aplicar o **SUNE**.

|                      Caso U                       |                      Caso Pi                       |                       Caso H                       |                       Caso T                       |                      Caso AS                       |                       Caso S                       |                       Caso L                       |
| :-----------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: | :------------------------------------------------: |
| <img src="Sune/9.png" alt="drawing" width="200"/> | <img src="Sune/10.png" alt="drawing" width="200"/> | <img src="Sune/11.png" alt="drawing" width="200"/> | <img src="Sune/12.png" alt="drawing" width="200"/> | <img src="Sune/13.png" alt="drawing" width="200"/> | <img src="Sune/14.png" alt="drawing" width="200"/> | <img src="Sune/15.png" alt="drawing" width="200"/> |



## Permutação dos Cantos (CMLL 2/2)

Nesse etapa os cantos da camada de **CIMA** serão finalizados, formando todos os pares nas laterais. Abaixo são mostrados os possíveis casos: nenhum par, um par ( <span style="color:orange">**Laranja**</span> no exemplo) e o objetivo dessa etapa, todos os pares.



|                   Nenhum Par                   |                     Um Par                     |                    Objetivo                    |
| :--------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: |
| <img src="J/1.png" alt="drawing" width="200"/> | <img src="J/2.png" alt="drawing" width="200"/> | <img src="J/3.png" alt="drawing" width="200"/> |

Para isso será usada a fórmula **J**, e seu efeito no cubo é trocar os cantos da **DIREITA** entre si. Sabendo disso, é necessário escolher qual posição da camada de **CIMA** o **J** vai ser aplicado. Basta seguir as regras:

1. Se houver um par, independentemente da cor, posicioná-lo na **ESQUERDA** e fazer o **J**
2. Se não, fazer o **J**, irá resultar em um par (caso **1** acima)

|                       J                        |                       R                        |                       U                        |                       R'                       |                       F'                       |                       R                        |                        U                        |
| :--------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: | :---------------------------------------------: |
| <img src="J/4.png" alt="drawing" width="200"/> | <img src="J/5.png" alt="drawing" width="200"/> | <img src="J/6.png" alt="drawing" width="200"/> | <img src="J/7.png" alt="drawing" width="200"/> | <img src="J/8.png" alt="drawing" width="200"/> | <img src="J/9.png" alt="drawing" width="200"/> | <img src="J/10.png" alt="drawing" width="200"/> |

|                       R'                        |                       U'                        |                       R'                        |                        F                        |                       R2                        |                       U'                        |                       R'                        |
| :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: |
| <img src="J/11.png" alt="drawing" width="200"/> | <img src="J/12.png" alt="drawing" width="200"/> | <img src="J/13.png" alt="drawing" width="200"/> | <img src="J/14.png" alt="drawing" width="200"/> | <img src="J/15.png" alt="drawing" width="200"/> | <img src="J/16.png" alt="drawing" width="200"/> | <img src="J/17.png" alt="drawing" width="200"/> |

## Orientação dos Meios (4a)

Agora começa a etapa chamada **Last Six Edges**, abreviada para **LSE**, que significa **Últimos 6 Meios** e é dividida em 3 fases. Nessa primeira fase, chamada de **Edge Orientation** ou simplesmente **EO**, o centro **Branco** ou <span style="color:#9c9720">**Amarelo**</span> deve ser posicionado na face de cima, fazendo **M** ou **M'**. Abaixo é mostrado o cubo com o centro **Branco** em cima, com destaque para os 6 meios (em **Preto**).

|                 4 Meios em CIMA                 |                 2 Meios EMBAIXO                 |
| :---------------------------------------------: | :---------------------------------------------: |
| <img src="4a/1.png" alt="drawing" width="200"/> | <img src="4a/2.png" alt="drawing" width="200"/> |

Os meios desorientados são aqueles que **NÃO** têm o **Branco** ou <span style="color:#9c9720">**Amarelo**</span> voltados para **CIMA** ou para **BAIXO**, e eles serão sempre em número **PAR**. Para orientá-los, serão usadas duas fómulas: a **SETA** e a **TROCA**.

A **SETA** tem esse nome pois as 3 peças de cima podem ser vistas como uma seta, apontando para um dos lados. Para resolvê-la, a "seta" deve apontar para a peça que está desorientada **EMBAIXO**. Essa peça de **BAIXO** pode estar na  **FRENTE** ou **ATRÁS**. No exemplo a seguir, a seta está apontando para a **DIREITA**, mas como a peça desorientada de **BAIXO** está na **FRENTE**,  camada de **CIMA** deve ser girada de forma a seta "apontar" para a **FRENTE**.

|                         Seta                         |                          U                           |
| :--------------------------------------------------: | :--------------------------------------------------: |
| <img src="4a/25seta.png" alt="drawing" width="200"/> | <img src="4a/26seta.png" alt="drawing" width="200"/> |

A **SETA** muda a orientação de 4 meios, os dois da **FRENTE** e os **LATERAIS**. Abaixo é mostrado o caso com 3 meios desorientados em **CIMA** e 1 **EMBAIXO** (3-1), bem como a fórmula da **SETA** para resolvê-lo, orientando todos os meios.

|                  Seta (Frente)                  |                       M'                        |                        U                        |                       M'                        |                                                 |
| :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | ----------------------------------------------- |
| <img src="4a/3.png" alt="drawing" width="200"/> | <img src="4a/4.png" alt="drawing" width="200"/> | <img src="4a/5.png" alt="drawing" width="200"/> | <img src="4a/6.png" alt="drawing" width="200"/> | <img src="4a/7.png" alt="drawing" width="200"/> |

Detalhe que esse caso (3-1) pode se apresentar também atrás, ou seja, o meio desorientado da camada de **BAIXO** está **ATRÁS**.  Para resolvê-lo o primeiro movimento deve ser **M**, como mostrado abaixo.

|                   Seta (Trás)                    |                        M                         |                        U                         |                        M'                        |
| :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: |
| <img src="4a/12.png" alt="drawing" width="200"/> | <img src="4a/13.png" alt="drawing" width="200"/> | <img src="4a/14.png" alt="drawing" width="200"/> | <img src="4a/15.png" alt="drawing" width="200"/> |

A **TROCA** não muda a orientação de nenhuma peça, mas sim troca os 2 meios da **FRENTE** entre si. Abaixo é mostrado o caso de 2 meios desorientados em **CIMA** e 2 **EMBAIXO** (2-2), bem como a fórmula da **TROCA** para transformá-lo no caso 3-1.

|                      Troca                      |                       M'                        |                        U2                        |                        M                         |
| :---------------------------------------------: | :---------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: |
| <img src="4a/8.png" alt="drawing" width="200"/> | <img src="4a/9.png" alt="drawing" width="200"/> | <img src="4a/10.png" alt="drawing" width="200"/> | <img src="4a/11.png" alt="drawing" width="200"/> |

Para resolver qualquer caso, basta seguir as regras:

1. Deixar somente **4** peças desorientadas usando a **SETA**
2. Usar a **TROCA** para deixar somente **1** das peças desorientadas **EMBAIXO**
3. Usar a **SETA** para orientar tudo

Abaixo são mostrados os casos possíveis de **EO** e como resolvê-los.

|  Nome  |                       Caso                       |                      Solução                       |
| :----: | :----------------------------------------------: | :------------------------------------------------: |
| (3-1)  | <img src="4a/16.png" alt="drawing" width="100"/> |                      **SETA**                      |
| (4-0)  | <img src="4a/17.png" alt="drawing" width="100"/> |              **TROCA ~> U2 ~> SETA**               |
| (2a-0) | <img src="4a/18.png" alt="drawing" width="100"/> |               **SETA ~> U2 ~> SETA**               |
| (2o-0) | <img src="4a/19.png" alt="drawing" width="100"/> |       **SETA ~> TROCA ~> U' ~> SETA ATRÁS**        |
| (2a-2) | <img src="4a/20.png" alt="drawing" width="100"/> |               **SETA ~> U ~> SETA**                |
| (2o-2) | <img src="4a/21.png" alt="drawing" width="100"/> |           **TROCA ~> U2 ~> SETA ATRÁS**            |
| (0-2)  | <img src="4a/22.png" alt="drawing" width="100"/> |            **SETA ~> U' ~> SETA ATRÁS**            |
| (1-1)  | <img src="4a/23.png" alt="drawing" width="100"/> |            **SETA ~> U ~> SETA ATRÁS**             |
| (4-2)  | <img src="4a/24.png" alt="drawing" width="100"/> | **SETA ~> U2 ~> SETA ~> TROCA ~> U ~> SETA ATRÁS** |



## Finalizar Lados Azul e Verde (4b)

Nessa etapa os meios <span style="color:green">**Verde**</span> e <span style="color:#9c9720">**Amarelo**</span> e <span style="color:blue">**Azul**</span> e <span style="color:#9c9720">**Amarelo**</span> serão resolvidos. Para isso, eles devem ser colocados **OPOSTOS** na camada de **BAIXO**. Abaixo é mostrado o caso em que a <span style="color:green">**Verde**</span> e <span style="color:#9c9720">**Amarelo**</span> e <span style="color:blue">**Azul**</span> e <span style="color:#9c9720">**Amarelo**</span> estão na camada de **CIMA** **ADJACENTES**, ou seja, uma ao lado da outra. Nesse caso, uma delas será colocada **EMBAIXO** com **M2**, e a outra com a **TROCA** na **FRENTE**.

|                     Exemplo                     |                       M2                        |                        U                        |                       M'                        |                       U2                        |                        M                        |
| :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: |
| <img src="4b/1.png" alt="drawing" width="200"/> | <img src="4b/2.png" alt="drawing" width="200"/> | <img src="4b/3.png" alt="drawing" width="200"/> | <img src="4b/4.png" alt="drawing" width="200"/> | <img src="4b/5.png" alt="drawing" width="200"/> | <img src="4b/6.png" alt="drawing" width="200"/> |

Também é possível que elas estejam **OPOSTAS** na camada de **CIMA**. Nesse caso, basta fazer **M2** para coloca-las na camada de **BAIXO**.

Agora basta seguir:

* observar a peça que está na **FRENTE**

* trazer o par **OPOSTO** na **FRENTE ** girando a camada de **CIMA** 

* fazer **M2** para encaixá-las

* girar a camada de **CIMA** para finalizar os lados <span style="color:green">**Verde** </span> e <span style="color:blue">**Azul** </span>

   

  No exemplo abaixo, a peça <span style="color:blue">**Azul**</span> e <span style="color:#9c9720">**Amarelo**</span> está na **FRENTE**, então o par <span style="color:green">**Verde**</span> deve ser posicionado na **FRENTE**.

|                     Exemplo                     |                       U2                        |                       M2                        |                       U'                        |
| :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: |
| <img src="4b/6.png" alt="drawing" width="200"/> | <img src="4b/7.png" alt="drawing" width="200"/> | <img src="4b/8.png" alt="drawing" width="200"/> | <img src="4b/9.png" alt="drawing" width="200"/> |

Neste outro, a peça <span style="color:green">**Verde**</span> e <span style="color:#9c9720">**Amarelo**</span> está na **FRENTE**. 

|                     Exemplo                      |                        U'                        |                        M2                        |                        U                         |
| :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: |
| <img src="4b/11.png" alt="drawing" width="200"/> | <img src="4b/12.png" alt="drawing" width="200"/> | <img src="4b/13.png" alt="drawing" width="200"/> | <img src="4b/14.png" alt="drawing" width="200"/> |

## Finalizar Camada M (4c)

Agora só falta a camada **M** para ser resolvida, isto é, 4 peças. Esta etapa se resume sempre em 2 **TROCAS**.  A maior parte dos casos é um **3-cycle**, ou seja, um **Ciclo de 3 peças**. No exemplo abaixo são mostradas a 4 peças da camada **M**.

|                     Exemplo                     |                       M'                        |                       M'                        |                       M'                        |
| :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: |
| <img src="4c/1.png" alt="drawing" width="200"/> | <img src="4c/2.png" alt="drawing" width="200"/> | <img src="4c/3.png" alt="drawing" width="200"/> | <img src="4c/4.png" alt="drawing" width="200"/> |

Figura 1: peça <span style="color:red">**Vermelho**</span> e <span style="color:#9c9720">**Amarelo**</span> entre os centros <span style="color:orange">**Laranja**</span> e **Branco**  ~> **COMPLETAMENTE ERRADA**

Figura 2: peça <span style="color:orange">**Laranja**</span> e <span style="color:#9c9720">**Amarelo**</span> entre os centros <span style="color:orange">**Laranja**</span> e <span style="color:#9c9720">**Amarelo**</span> ~> **COMPLETAMENTE CERTA**

Figura 3: peça <span style="color:red">**Vermelho**</span> e **Branco** entre os centros <span style="color:red">**Vermelho**</span> e <span style="color:#9c9720">**Amarelo**</span> 

Figura 4: peça <span style="color:orange">**Laranja**</span> e **Branco** entre os centros <span style="color:red">**Vermelho**</span> e **Branco**

Para resolvê-lo basta seguir:

* Deixar a peça **COMPLETAMENTE ERRADA** na camada de **CIMA** girando a camada **M**
* Deixar a peça **COMPLETAMENTE CERTA** na camada de **BAIXO** girando a camada **M**
* Trocar as peças de **CIMA** com **U2**

Esse processo irá criar outra peça **COMPLETAMENTE CERTA**. Então basta fazer:

* Deixar as 2 peças **COMPLETAMENTE CERTAS** na camada de **BAIXO** girando a camada **M**
* Trocar as peças de **CIMA** com **U2**
* Girar a camada **M** para finalizar o Cubo.

Abaixo é mostrado um exemplo.

|                     Exemplo                     |                       M2                        |                       U2                        |                        M                        |                       U2                        |                        M                        |
| :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: |
| <img src="4c/3.png" alt="drawing" width="200"/> | <img src="4c/1.png" alt="drawing" width="200"/> | <img src="4c/5.png" alt="drawing" width="200"/> | <img src="4c/6.png" alt="drawing" width="200"/> | <img src="4c/7.png" alt="drawing" width="200"/> | <img src="4c/8.png" alt="drawing" width="200"/> |

Pode acontecer de não haver nenhuma peça **COMPLETAMENTE ERRADA**. Nesse caso, as duas trocas vão acontecer na **HORIZONTAL**l ou na **VERTICAL**, como nos exemplos.

|                   Horizontal                    |                        U2                        |                        M2                        |                        U2                        |                       M2                        |
| :---------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :---------------------------------------------: |
| <img src="4c/9.png" alt="drawing" width="200"/> | <img src="4c/10.png" alt="drawing" width="200"/> | <img src="4c/11.png" alt="drawing" width="200"/> | <img src="4c/12.png" alt="drawing" width="200"/> | <img src="4c/8.png" alt="drawing" width="200"/> |



|                     Vertical                     |                        M'                        |                        U2                        |                        M2                        |                        U2                        |                        M                        |
| :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :---------------------------------------------: |
| <img src="4c/13.png" alt="drawing" width="200"/> | <img src="4c/14.png" alt="drawing" width="200"/> | <img src="4c/15.png" alt="drawing" width="200"/> | <img src="4c/16.png" alt="drawing" width="200"/> | <img src="4c/17.png" alt="drawing" width="200"/> | <img src="4c/8.png" alt="drawing" width="200"/> |

Por fim, pode acontecer de todas as peças estarem **COMPLETAMENTE ERRADAS** ou **TODOS OS CENTROS**. Nesses casos, chamados de **DOTS**, é mais vantajoso trocar os centros entre si.

|                       Dots                       |                        E2                        |                        M                         |                        E2                        |                        M                        |
| :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :---------------------------------------------: |
| <img src="4c/18.png" alt="drawing" width="200"/> | <img src="4c/19.png" alt="drawing" width="200"/> | <img src="4c/20.png" alt="drawing" width="200"/> | <img src="4c/21.png" alt="drawing" width="200"/> | <img src="4c/8.png" alt="drawing" width="200"/> |

|                       Dots                       |                        E2                        |                        M                         |                        E2                        |                       M'                        |
| :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :----------------------------------------------: | :---------------------------------------------: |
| <img src="4c/22.png" alt="drawing" width="200"/> | <img src="4c/23.png" alt="drawing" width="200"/> | <img src="4c/24.png" alt="drawing" width="200"/> | <img src="4c/25.png" alt="drawing" width="200"/> | <img src="4c/8.png" alt="drawing" width="200"/> |

##                            