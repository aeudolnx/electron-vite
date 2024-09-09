# Projeto React + Vite + Electron

Este projeto é uma aplicação desktop que combina React com Vite e Electron. A seguir, você encontrará instruções sobre como instalar as dependências e realizar o build da aplicação.

## 🚀 Instalação

Para começar, clone o repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
npm install


🛠 Scripts
Desenvolvimento
Para iniciar o servidor de desenvolvimento: npm run dev

Este comando iniciará o Vite no modo de desenvolvimento e abrirá a aplicação Electron.

Build
Para construir a aplicação para produção:

  1 - Build da aplicação Vite: npm run build

Este comando criará a build da aplicação React no diretório dist.

  2 - Build do aplicativo Electron: npx electron-builder


Este comando empacota a aplicação Electron junto com a build gerada pelo Vite. O resultado será um executável para a plataforma em que você está trabalhando, localizado no diretório dist.

⚙️ Configuração
Vite: As configurações do Vite estão localizadas em vite.config.js.
Electron: O ponto de entrada da aplicação Electron está em electron/main.js.
🚧 Problemas Comuns
Erro de ESLint: Se encontrar problemas com ESLint relacionados ao tsconfig.json, verifique se o arquivo está corretamente configurado para incluir todos os arquivos necessários.
```
