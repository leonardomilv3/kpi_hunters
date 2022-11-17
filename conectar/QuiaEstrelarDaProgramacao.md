# Quia Estrelar da Programação

## O que é Programar?

1. Programa

- Utiliza **Algoritmos** e **Lógica de Programação**.

2. Como computador pensa e entende?

- Não pensa! Apenas processa e calcula.
- Recebe ordens através de **Linguagens de Programação**.
- É necessário entender os problemas para dar ordens.

3. Dar Instruções

- Recebe dados, manipula-os e gera um retorno.
- Os dados podem ser: **String, Numérico, Boolean**.
- Exemplos: intruções para nadar, fazer café, ligar a tv.


4. Resolver problemas.

- A chave é **entender os problemas**.

## Como funciona a WEB?

1. Digita uma URL rocketseat.com.br

- **HTTP**: HyperText Transfer Protocol.
    - Função: trocar mensagem entre computadores.
    - A mensagem é quebrada em diversos pedaços (**chunks**).
- **URL**: Uniform Resource Locator.
    - Localizador e indentificador de um recurso.
    - Recurso, nesse caso, é o site.

2. É inicada uma linha de comunicação através do protocolo TCP, entre o seu computador (**cliente**), até o computador que possui a página (**servidor**).

- **Cliente**: Computador, dispositivo ou aplicativo que fez o pedido.
- **Sevidor**: Computador configurado para receber o pedido.
- **TCP**: Transmission Control Protocol.
    - Função: garantir que seus pacotes cheguem corretamente ao seu destino.

3. O endereço é convertido em um IP (76.76.21.21) através do DNS

- **IP**: Internet Protocol.
    - Função: endereçamento dos computadores.
- **DNS**: Domain Name Service.
    - Função: converter um domínio em um endereço de IP.

4. Seu pedido está percorrendo diversos proxies

- **Proxy**: Qualquer dispositivo no meio do caminho. Exemplo: modem, roteadores.
    - Função: encaminhamento dos pacotes.

5. Seu pedido chega até o servidor.

6. Servidor analisa o seu pedido e te dá uma resposta, nesse caso, positiva.

7. O  caminho de volta é semelhante ao de ida, passando pela linha de comunicação que foi criada.

8. O browser recebe os pedaços (chunks) e monta a tela do site para você.

9. Esse process acontece muitas vezes, pois para cada recurso (html, css, javascript, imagem ...), é feita uma nova conexão.

