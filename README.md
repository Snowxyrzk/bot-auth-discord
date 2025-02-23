<a href="#"><img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&color=2ad3ff&text=AUTORIZER&fontColor=fffefe&fontAlign=50&fontAlignY=30&fontSize=35"/></a>


# Discord OAuth2 Verification Bot
*desenvolvido por:  _[!im Snow?](https://guns.lol/imsnow)_*

# NOSSO DISCORD!
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gamesdest)

Este projeto é um bot para Discord que utiliza OAuth2 para autenticar usuários e adicioná-los automaticamente ao servidor.

## 🏂Funcionalidades
<details>
  <summary>Mostrar funcionalidades </summary>
  
  - Autenticação via Discord OAuth2
  - Adição automática de usuários ao servidor após a autenticação
  - Servidor Express para gerenciar o fluxo de autenticação
  - Autentificação para bots e sites


## 🛠️ Pré-requisitos
  <summary>ver requisitos</summary>
<details>
  Antes de começar, você precisará ter instalado em sua máquina:

  1. **[Node.js](https://nodejs.org/)**  
     Certifique-se de ter o Node.js instalado, pois ele é necessário para rodar o código. Se você não tiver, baixe e instale a versão mais recente estável.

  2. **[NPM](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)**  
     O NPM (Node Package Manager) vem junto com o Node.js. Se preferir, você pode usar o Yarn como alternativa para gerenciar pacotes.

  3. **Conta de Desenvolvedor no [Discord Developer Portal](https://discord.com/developers/applications)**  
     Você precisará criar uma aplicação no Discord Developer Portal para obter o **Client ID**, **Client Secret** e **Bot Token**. Isso é necessário para autenticar usuários e adicionar o bot ao servidor.

  4. **Servidor no Discord**  
     Você precisa de um servidor no Discord onde o bot será adicionado automaticamente após o processo de autenticação. Certifique-se de ter o **Guild ID** do servidor.

  5. **[Visual Studio Code](https://code.visualstudio.com/)** (opcional, mas recomendado)  
     O VS Code é um editor de código altamente recomendado para trabalhar com Node.js, pois oferece recursos como depuração, auto-completar e controle de versão integrado. Baixe e instale o Visual Studio Code para facilitar o desenvolvimento.

  6. **Plataformas de Hospedagem**  
     Para rodar a aplicação em produção, você precisará de um serviço de hospedagem. Algumas opções incluem:
     - **[Vercel](https://vercel.com/)**  
     - **[Railway](https://railway.app/)**  
     - **[Glitch](https://glitch.com/)**  
     - **[DigitalOcean](https://www.digitalocean.com/)**  
     - **[Square](https://developer.squareup.com/)** (se você precisar integrar com pagamento ou outras funcionalidades da Square)

</details>



## 🔧 Configuração
<details>
  <summary>Mostrar configuração </summary>

  ### 🖥️ Ferramentas necessárias
  Antes de começar, instale as seguintes ferramentas:
  - [Visual Studio Code (VS Code)](https://code.visualstudio.com/)
  - [Node.js](https://nodejs.org/) (inclui o gerenciador de pacotes NPM)
  - [Git](https://git-scm.com/) (para clonar o repositório

  ### 📦 Instalando dependências
  No terminal, dentro da pasta do projeto, execute:
  ```bash
  npm install
  ```
  Dependências utilizadas:
  - `discord.js`
  - `axios`
  - `express`

  ### ⚙️ Configurando credenciais
  Crie um arquivo `.env` na raiz do projeto e adicione suas credenciais do Discord:
  ```ini
  CLIENT_ID=SEU_CLIENT_ID
  CLIENT_SECRET=SEU_CLIENT_SECRET
  BOT_TOKEN=SEU_BOT_TOKEN
  GUILD_ID=SEU_GUILD_ID
  REDIRECT_URI=http://localhost:3001/callback
  ```

  ### ▶️ Iniciando o servidor
  Para rodar o bot, execute:
  ```bash
  node index.js
  ```

  ### 🌐 Acessando a verificação
  - Abra o navegador e vá até `http://localhost:3001`
  - Clique no botão "Verificar"
  - Após se autenticar no Discord, você será automaticamente adicionado ao servidor 🎉

</details>

## 📁 Baixar

<details>
  <summary>Baixar/zip </summary>
  
  **[Clique aqui para baixar](https://cdn.discordapp.com/attachments/1326756804889280553/1343342038828974110/bot_auth.zip?ex=67bcec44&is=67bb9ac4&hm=c321c7af3fa5b7516ddfb95b740ec12d77f4ed9c7f472fc94f9aca0ef77a031d&)**
  
</details>



## 📝 Como funciona

1. O usuário acessa `http://localhost:3001` e clica no botão "Verificar".
2. O usuário é redirecionado para o Discord para conceder permissões ao bot.
3. Após autorizar, o usuário retorna ao site e é automaticamente adicionado ao servidor.

## 📜 Licença
**SE FOR USAR DÊ OS CREDITOS POR FAVOR.**

![Desenvolvido por: !im Snow?](https://i.pinimg.com/736x/e9/c0/77/e9c0776e9887a57f0851c34316112e03.jpg)
# *By:* _[!im Snow?](https://guns.lol/imsnow)_


