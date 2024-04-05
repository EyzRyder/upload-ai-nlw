<h1 align="center" style="text-align: center;">
  upload.ai
</h1>

<p align="center">
  <a href="#Projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Utilização">Utilização</a>
</p>


## 📂 Projeto

Aplicação que possibilita realizar upload de videos e por meio de IA, criar automaticamente títulos chamativos e descrições com um boa indexação. Alem disso pode fazer muito ,ais dependedno do promopt

### [Front-end](https://github.com/EyzRyder/upload-ai-nlw/tree/main/web)
No front-end é um form onde videos são upados, selecione o prompt e masi coisas adicionais, nisso é mandado um requisição para o api, sendo devolvido algo referento o video do que foi pedido no promt. 

### [Back-end](https://github.com/EyzRyder/upload-ai-nlw/tree/main/api)
No Back-end é um server que baixa os videos, transforma o video em audio e é intepretado pelo ia gerando um resposta de a cordo com o prompt. 

## 💻 Tecnologias

Este projeto foi desenvolvido utilizando tecnologias como:

- Node.js
- TypeScript
- Fastify
- Prisma
- Dotenv
- OpenAI
- Zod


## 💡 Utilização

Para executar a aplicação em sua máquina localmente, certifique-se de ter o `Node.js` e o `npm` instalados antes de prosseguir com as etapas abaixo:

1. Clone o projeto:

```
$ git clone https://github.com//EyzRyder/upload-ai-nlw
```

2. Acesse a pasta do projeto:

```
$ cd upload-ai-nlw
```

3. Instale as dependências:

```
$ npm install
```

4. Execute as migrações:

```
$ npx prisma migrate dev
```

5. Inicie o servidor:

```
$ npm run dev
```

⚠️ **Obs. Importante**: Crie um arquivo .env de acordo com o arquivo .env.example. No campo DATABASE_URL, especifique a URL do banco de dados que deseja utilizar. Crie uma conta no site [OpenAI](https://openai.com/), obtenha sua chave da API e preencha o campo OPENAI_KEY com sua chave.


---

Feito com 💛 by Gabriel Bessi 
