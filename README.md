# Upload.ai

O Upload.ai é um projeto criado durante a NLW IA da Rocketseat que utiliza inteligência artificial para gerar transcrições de vídeos automaticamente. Com ele, você pode fazer o upload de um vídeo e obter uma transcrição precisa em questão de segundos, além de usar um prompt para criar títulos e descrições para seus vídeos usando IA.

![Screenshot do Projeto](https://imgur.com/43tNBZb.png)

## Instalação

### Front-end

1. Navegue até a pasta do front-end:

``` 
cd upload-ai-web
```


2. Instale as dependências:
```
npm install
```  


3. Execute o front-end:

```
npm run dev
``` 


### Back-end

1. Navegue até a pasta do back-end:
```
cd upload-ai-api
```


2. Instale as dependências:

```
npm install
```


3. Renomeie `.example.env` para `.env`:
```
mv .examle.env .env
``` 

4. Coloque sua chave da OpenAI em `OPENAI_KEY` dentro do arquivo `.env`

4. Inicie o servidor:
```
npm run dev
``` 

Após iniciar o back-end e o front-end, acesse a aplicação em seu navegador utilizando a seguinte URL: [http://localhost:5173](http://localhost:5173)

## Tecnologias Utilizadas

- Langchain: Plataforma de processamento de linguagem natural para melhorar a precisão da transcrição.
- React: Biblioteca JavaScript para a construção da interface do usuário.
- Next.js: Framework React para desenvolvimento web.
- Node.js: Ambiente de tempo de execução JavaScript para o servidor.
- OpenAI: API de inteligência artificial para reconhecimento de fala e processamento de texto.
- Tailwind CSS: Framework CSS para estilização rápida e responsiva.
- TypeScript: Linguagem de programação que adiciona tipagem estática ao JavaScript.
- Vercel AI SDK: SDK para integração com os serviços de IA da Vercel.

## Autor

Feito por [João Victor](https://github.com/Vitinho163).