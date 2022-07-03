# Guia Estelar de Programação

## Programar

Algoritmos -> sequência lógica para resolver problemas

Lógica de programação -> aplicação dos algoritmos


## Como funciona a WEB

Protocolo HTTP (Hypertext Transfer Protocol) -> responsável pela troca de mensagens (pacotes) entre computadores

URL (Uniform Resource Locator) -> localizador e identificador de recursos

Comunicação Cliente/Servidor através de protocolo TCP:

- Cliente: o browser faz o pedido
- Servidor: recebe os pedidos e envia as respostas desses pedidos
- TCP (Transmission Control Protocol): responsável por garantir que os pacotes cheguem ao destino

O endereço (URL) é convertido em um IP através do DNS.
- IP (Internet Protocol): responsável pelo endereçamento dos computadores
- DNS (Domain Name Servers): responsável pela conversão de um domínio em um endereço de IP

exemplo de domínio: https://rocketseat.com.br

exemplo de IP: 76.76.21.21

Proxy: responsável pelo encaminhamento dos pacotes

**Caminho da WEB:**

1. URL
2. início da comunicação via TCP
3. conversão do IP via DNS
4. pedido percorre proxies
5. pedido chega ao servidor
6. servidor analisa e retorna uma resposta
7. a resposta percorre o mesmo caminho
8. o browser recebe o pacote e monta a tela do site