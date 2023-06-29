
# Whats-GPT

Este projeto permite o uso do ChatGPT, um modelo de linguagem avançado baseado em inteligência artificial, diretamente no WhatsApp. Além disso, também disponibiliza o recurso de transcrição de áudios, fazendo consumo da API da OpenAI, utilizando os modelos GPT e Whisper.

## Instalação

Para utilizar este projeto de forma local, siga as instruções abaixo:

1. Clone o repositório para o seu ambiente local. 
     `git clone https://github.com/eliasnsz/whats-gpt.git`
2.  Execute o comando `npm install` para instalar as dependências necessárias.
3.  Adicione sua [chave de API](https://platform.openai.com/account/api-keys) da OpenAI em um arquivo .env, seguindo o modelo do `.env.example`.
4.  Execute o comando `npm run build`  .
5.  Execute o comando `npm start`  .
6.  No whatsapp, faça a leitura do QRCode que foi gerado no console.
7. Aguarde a mensagem `"Client is ready!"` aparecer no console.
8. Pronto!

## Uso

### ChatGPT:
Para utilizar o ChatGPT basta incluir `!` antes das suas mensagens:

![](https://i.imgur.com/WIW9PU0.jpg)

Essa feature funciona tanto em conversas individuais quanto em grupos, desde que você esteja presente neles. Ele pode ser utilizado por todas as pessoas participantes da conversa, permitindo que cada uma delas faça perguntas e obtenha respostas do modelo.

### Transcrição de áudios:
Para utilizar a transcrição de áudios basta dizer a palavra-chave **`Transcreva`** durante sua gravação:

![](https://i.imgur.com/MNIt4wn.jpg)

Essa feature, do mesmo modo que a anterior, funciona em conversas individuais e em grupos que você esteja incluso.

## Contribuição

Contribuições são bem-vindas! Se você tiver ideias para refatorar o código existente, implementar novos recursos ou melhorar a usabilidade do projeto, fique à vontade para contribuir.

