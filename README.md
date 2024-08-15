
<img src="https://img.freepik.com/fotos-premium/simbolo-de-reciclagem-de-neon-brilhante-representando-praticas-sustentaveis-modernas_38013-19715.jpg?w=740" width="1000" height="400">

# EWASTE API🔋 <a name="titulo-e-imagem-de-capa"></a>

## Introdução📄 <a name="introducao"></a>

A API e-waste foi criada para enfrentar o problema do descarte inadequado de resíduos eletrônicos no Brasil, que é o quinto maior gerador mundial de e-lixo, com uma taxa de reciclagem de menos de 3%. Ela facilita o acesso a pontos de coleta, oferece recompensas por práticas sustentáveis e permite que usuários encontrem locais de descarte e verifiquem cupons de desconto. Empresas parceiras cadastram seus pontos de coleta, e administradores gerenciam as categorias de itens. A API promove a sustentabilidade, reduz o descarte incorreto e fortalece a responsabilidade ambiental das empresas.

Este projeto foi desenvolvido como parte do Módulo 4 da formação FullStack do Instituto Programadores do Amanhã.

Acesse o link do slide : [EWASTE API SLIDE](https://www.canva.com/design/DAGNd0V7dTI/t28Q1JnbW0DKUd2ZK57S3w/view?utm_content=DAGNd0V7dTI&utm_campaign=designshare&utm_medium=link&utm_source=editor)

Link Deploy: https://squad4-projeto-final-m4.onrender.com/


## Índice🔗  <a name="indice"></a>

* [Título e Imagem de capa](#titulo-e-imagem-de-capa)
* [Introdução](#introducao)
* [Índice](#indice)
* [Funcionalidades do Projeto](#funcionalidades-do-projeto)
* [Teconlogias Utilizadas](#tecnologias-utilizadas)
* [Estrutura do Projeto](#estrutura-do-projeto)
* [Modelagem de Dados](#modelagem-de-dados)
* [Configuração do Projeto](#configuraçao-do-projeto)
* [Pessoas Desenvolvedoras](#pessoas-desenvolvedoras)
* [Licença](#licenca)



## Funcionalidades do projeto⚙️   <a name="funcionalidades-do-projeto"></a>

Confira o link da documentação do Swagger: [EWASTE API SWAGGER](https://squad4-projeto-final-m4.onrender.com/api-docs/)


## Tecnologias Utilizadas💻 <a name="tecnologias-utilizadas"></a>

* Node.js
* Express
* JavaScript
* PostgreSQL
* Render (para o deploy)
* Swagger (para documentação)
* UUID (para geração de IDs exclusivos)


## Estrutura do Projeto📁 <a name="estrutura-do-projeto"></a>
- **server.js/**: servidor da aplicação.
- **src/routes/.js**: arquivos de configuração das rotas.
- **src/controllers/**: arquivos de lógica de controle das requisições.
- **src/models/**: arquivos que definem os modelos de dados.
- **src/database/**: configuração da conexão com o banco de dados.
- **src/config/**: configuração do Swagger e CORS.


## Modelagem de Dados🎲 <a name="modelagem-de-dados"></a>

Link do esquema de banco de dados: [DB Diagram West API](https://dbdiagram.io/d/miniprojeto-m3[updated]-663851ae5b24a634d092fe70)

## Configuração do Projeto🔧 <a name="configuracao-do-projeto"></a>

### Pré-requisitos
* Node.js instalado
* npm (Node Package Manager) ou yarn

### Instalação
1. Clone o repositório
```bash
https://github.com/ste-coding/miniprojeto-api-M4.git
```

2. Instale as dependências
```bash
npm install bcrypt cors dotenv sequelize pg pg-hstore express
```
3. Para iniciar o servidor de desenvolvimento, use:
```bash
npm start
```

## Pessoas Desenvolvedoras🧑‍💻  <a name="pessoas-desenvolvedoras"></a>
<style>
  #image {
    height: 115px
  }
  #title {
    font-size: 11.5px;
  }

</style>
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/ste-coding">
        <img src="https://avatars.githubusercontent.com/u/83964857?v=4" width="115" alt="Stéphanie Cândido" id="image"/><br/>
        <sub id="title"><b>Stéphanie Cândido</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Monteiro-Let">
        <img src="https://avatars.githubusercontent.com/u/154276458?s=400&u=1526f34b9402fadbe89b685308ed1224f27e717e&v=4" width="115" alt="Letícia Monteiro" id="image"/><br/>
        <sub><b>Letícia Monteiro</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/samiferreira">
        <img src="https://avatars.githubusercontent.com/u/128096328?v=4" width="115" alt="Samira Ferreira" id="image"/><br/>
        <sub><b>Samira Ferreira</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/andreirce">
        <img src="https://avatars.githubusercontent.com/u/154296627?v=4" width="115" alt="Andrei Levi" id="image"/><br/>
        <sub><b>Andrei Levi</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/hewelbelmonte">
        <img src="https://avatars.githubusercontent.com/u/130703340?v=4" width="115" alt="Hewel Belmonte" id="image"/><br/>
        <sub><b>Hewel Belmonte</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/DeboraVitoria0">
        <img src="https://cdn.discordapp.com/attachments/1272754250266578974/1273430138498973726/foto_perfil.jpg?ex=66be95bc&is=66bd443c&hm=0d7ef141e05a00b1efbcf47d29d717fe1ab241b14e97da67ff83889ef36b3ac9&" width="115" alt="Débora Vitória" id="image"/><br/>
        <sub><b>Débora Vitória</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/GabrielRER">
        <img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcTAFXrpV2sIWI8L_o4AX76NN2FPnznJapMmMyOUfCNg2Bc8vugQ" width="115" alt="Gabriel Ramon" id="image"/><br/>
        <sub><b>Gabriel Ramon</b></sub>
      </a>
    </td>
  </tr>
</table>

## Licença🔓  <a name="licenca"></a>
Este projeto é lincensiado por :[Licença GPL-3.0](https://github.com/ste-coding/squad4-projeto-final-M4?tab=GPL-3.0-1-ov-file)