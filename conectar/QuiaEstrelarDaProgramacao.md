# Quia Estrelar da Programação

## O que é Programar?

1. Programa

&emsp;&emsp; - Utiliza **Algoritmos** e **Lógica de Programação**.

2. Como computador pensa e entende?

&emsp;&emsp; - Não pensa! Apenas processa e calcula.
&emsp;&emsp; - Recebe ordens através de **Linguagens de Programação**.
&emsp;&emsp; - É necessário entender os problemas para dar ordens.

3. Dar Instruções

&emsp;&emsp; - Recebe dados, manipula-os e gera um retorno.
&emsp;&emsp; - Os dados podem ser: **String, Numérico, Boolean**.
&emsp;&emsp; - Exemplos: intruções para nadar, fazer café, ligar a tv.


4. Resolver problemas.

&emsp;&emsp; - A chave é **entender os problemas**.

## Como funciona a WEB?

1. Digita uma URL https://rockseat.com.br

&emsp;&emsp; - **HTTP**: HyperText Transfer Protocol.
&emsp;&emsp;&emsp;&emsp;- Função: trocar mensagem entre computadores.
&emsp;&emsp;&emsp;&emsp;- A mensagem é quebrada em diversos pedaços (**chunks**).
&emsp;&emsp; - **URL**: Uniform Resource Locator.
&emsp;&emsp;&emsp;&emsp;- Localizador e indentificador de um recurso.
&emsp;&emsp;&emsp;&emsp;- Recurso, nesse caso, é o site.

2. É inicada uma linha de comunicação através do protocolo TCP, entre o seu computador (**cliente**), até o computador que possui a página (**servidor**).

&emsp;&emsp; - **Cliente**: Computador, dispositivo ou aplicativo que fez o pedido.
&emsp;&emsp; - **Sevidor**: Computador configurado para receber o pedido.
&emsp;&emsp; - **TCP**: Transmission Control Protocol.
&emsp;&emsp;&emsp;&emsp;- Função: garantir que seus pacotes cheguem corretamente ao seu destino.

3. O endereço é convertido em um IP (76.76.21.21) através do DNS

&emsp;&emsp; - **IP**: Internet Protocol.
&emsp;&emsp;&emsp;&emsp;- Função: endereçamento dos computadores.
&emsp;&emsp; - **DNS**: Domain Name Service.
&emsp;&emsp;&emsp;&emsp;- Função: converter um domínio em um endereço de IP.

4. Seu pedido está percorrendo diversos proxies

&emsp;&emsp; - **Proxy**: Qualquer dispositivo no meio do caminho. Exemplo: modem, roteadores.
&emsp;&emsp;&emsp;&emsp;- Função: encaminhamento dos pacotes.

5. Seu pedido chega até o servidor.

6. Servidor analisa o seu pedido e te dá uma resposta, nesse caso, positiva.

7. O  caminho de volta é semelhante ao de ida, passando pela linha de comunicação que foi criada.

8. O browser recebe os pedaços (chunks) e monta a tela do site para você.

9. Esse process acontece muitas vezes, pois para cada recurso (html, css, javascript, imagem ...), é feita uma nova conexão.

