<a href="#"><img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=150&color=2ad3ff&text=AUTORIZER&fontColor=fffefe&fontAlign=50&fontAlignY=30&fontSize=35"/></a>


# Discord OAuth2 Verification Bot

Este projeto é um bot para Discord que utiliza OAuth2 para autenticar usuários e adicioná-los automaticamente ao servidor.

## 🏂Funcionalidades>
<details>
  <summary>Mostrar funcionalidades ▼</summary>
  
  - Autenticação via Discord OAuth2
  - Adição automática de usuários ao servidor após a autenticação
  - Servidor Express para gerenciar o fluxo de autenticação
  - Autentificação para bots e sites

</details>


## 🛠️ Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina:
- [Node.js](https://nodejs.org/)
- [NPM](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)

## 🔧 Configuração

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. <details>
   <summary>Instale as dependências ▼</summary>
   
   ```bash
   npm install
   ```
   Dependências utilizadas:
   - `discord.js`
   - `axios`
   - `express`
   
   </details>

3. Crie um arquivo `.env` e adicione suas credenciais do Discord:
   ```ini
   CLIENT_ID=SEU_CLIENT_ID
   CLIENT_SECRET=SEU_CLIENT_SECRET
   BOT_TOKEN=SEU_BOT_TOKEN
   GUILD_ID=SEU_GUILD_ID
   REDIRECT_URI=http://localhost:3001/callback
   ```

4. Inicie o servidor:
   ```bash
   node index.js
   ```

5. Acesse `http://localhost:3001` e clique no botão para verificar seu Discord. Após se verificar, você será automaticamente adicionado ao servidor.

## 📝 Como funciona
<details>
  <summary>Mostrar explicação ▼</summary>
  
  1. O usuário acessa `http://localhost:3001` e clica no botão "Verificar".
  2. O usuário é redirecionado para o Discord para conceder permissões ao bot.
  3. Após autorizar, o usuário retorna ao site e é automaticamente adicionado ao servidor.

</details>

## 📜 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
Criado por [Seu Nome](https://github.com/seu-usuario) 🚀




3. Crie um arquivo `.env` e adicione suas credenciais do Discord:
   ```ini
   CLIENT_ID=SEU_CLIENT_ID
   CLIENT_SECRET=SEU_CLIENT_SECRET
   BOT_TOKEN=SEU_BOT_TOKEN
   GUILD_ID=SEU_GUILD_ID
   REDIRECT_URI=http://localhost:3001/callback
   ```

4. Inicie o servidor:
   ```bash
   node index.js
   ```

5. Acesse `http://localhost:3001` e clique no botão para verificar seu Discord. Após se verificar, você será automaticamente adicionado ao servidor.

## 📝 Como funciona
<details>
  <summary>Mostrar explicação ▼</summary>
  
  1. O usuário acessa `http://localhost:3001` e clica no botão "Verificar".
  2. O usuário é redirecionado para o Discord para conceder permissões ao bot.
  3. Após autorizar, o usuário retorna ao site e é automaticamente adicionado ao servidor.

</details>

## 📜 Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
Criado por [Seu Nome](https://github.com/seu-usuario) 🚀

