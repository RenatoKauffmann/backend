# Readme

## Criar uma Pasta:

>botão direito na area de trabalho;
>
>novo;
>
>pasta;
>
>de um nome a pasta;

## Cmd:

>Acesse 'desktop' (cd desktop)
>
>Acesse a pasta criada; (cd 'nome da pasta')
>
>Digite: 'node .' para acessar o Vs Code;
>
 
## Vs Code:

>Crie um arquivo (javascript);
>
* exe: apt.js
>Na linha de código:
const express = require('express');

const app = express();

app.use(express.json())

app.get('/', (req, res) => {

res.json({ msg:”Olá” });

});

app.listen(3000);


>Em seguida abra o terminal:
>
>Inicie um projeto com npm:
>
>npm init -y;
>
>
>Instale o Express:
>
>npm install express;
>
>Após concluir execute o servidor:
>
>Acesse o navegador;
>
>digite na barra de navegação: localhost:3000/

# Node.js
* Node.js é um ambiente de execução JavaScript que permite executar código no lado do servidor. Baseado no motor V8 do Google, utiliza uma arquitetura orientada a eventos e não bloqueante, tornando-o eficiente para gerenciar múltiplas conexões simultaneamente. É ideal para aplicações que exigem alta performance em I/O, como servidores web e APIs. Com o gerenciador de pacotes NPM, facilita a instalação de bibliotecas, e sua modularidade e suporte a frameworks como Express.js tornam o desenvolvimento mais ágil.


# API 

* Uma API (Interface de Programação de Aplicações) é um conjunto de regras que permite a comunicação entre sistemas de software, definindo como eles interagem e trocam dados. Existem diferentes tipos de APIs, incluindo APIs Web (como REST e SOAP), APIs de Sistema e APIs de Hardware. Elas utilizam protocolos como HTTP para comunicação e frequentemente requerem autenticação, como API Keys ou OAuth, para garantir a segurança. As APIs são essenciais para facilitar a integração entre serviços, acelerar o desenvolvimento e permitir a reutilização de funcionalidades em aplicações modernas e interconectadas.
