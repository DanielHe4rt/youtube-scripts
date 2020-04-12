# Tudo que você precisa saber antes de codar um bot

Video começa do fim, pausa dramática a ~ la stevie ~ freeza a tela e começa a falar sobre o video.

"Eae rapaziada! Calma que eu vou explicar esse final do video ai logo menos, mas antes já deixa o like favorito e vem comigo que eu vou te ensinar a criar os melhores bots da internet."

"Antes de começarmos a escrever qualquer aplicação, precisamos entender alguns fundamentos para começar a explorar as aplicações alheias e criar algo em cima delas."

"Vamos por partes e começando por o que são requisições http"

## Requisições HTTP

HTTP é um protocolo baseado em streams de textos onde o cliente abre uma chamada para o servidor, onde é enviado cabeçalhos e dados para que o servidor identifique e execute alguma ação e retorne a mesma.

Isso é dado como "requests" e "responses" e nunca haverá algum dado no corpo da resposta, porém identificaremos esses casos e quando aproveitarmos.

### Tipos de Requisições

Agora que sabemos um básico sobre requisições, precisamos saber quando e como elas são usadas. Iremos falar apenas de três principais para criação de qualquer tipo de bot que colete dados e execute ações simples sendo elas: GET, POST e DELETE.

- GET - Retorna dados e nunca deverá gerar algo novo e é representado sempre com um retorno os status 2xx.
  (explicação)

- POST - Cria algo novo do lado do servidor e tem como retorno os status 200 e 201
  (explicação)

- DELETE - Deleta algo do lado do servidor e tem como retorno o status 200 caso seja sucesso.
  (explicação)

### Status de requisições

Falar sobre tipos de status e os mais esperados do nosso lado (200, 201, 404, 500)

- 2xx - Sucesso
- 3xx - Redirecionamento
- 4xx - Informações erroneas mandada pelo cliente
- 5xx - Erro do servidor

### Tipos de Retorno

- Retornos de texto - Raramente são usados
- Retornos XML - Juro pra vc q nunca vi nada do tipo
- Retornos JSON - Mais comum em API's atuais e provavelmente você irá lidar com eles 99% do tempo.

## Network Sniffing

Análise de pacotes no networking do browser e explicando baseado nas requisições que você tiver.

Fazer em video analisando a API de Instagram, Reddit e Twitter com duração máxima de 3 minutos para isso tudo.

## Consumindo (Escolha sua linguagem)

Explicar a usabilidade da libcurl
Como encontrar um pacote referente a linguagem e dar sugestões.

## Finalização

Agora que você entendeu a base toda de como fazer o sniffing e interpretar pacotes de um jeito geral, você pode criar qualquer tipo de bot ou script para automatizar algo na web.
