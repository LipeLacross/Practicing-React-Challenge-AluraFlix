## 🌐 [English Version of README](README_EN.md)

# AluraFlix

AluraFlix é uma plataforma inspirada no Netflix, desenvolvida como parte de um projeto educacional. O objetivo é criar uma aplicação web para compartilhar e categorizar vídeos educativos, oferecendo uma interface intuitiva e responsiva.

## 🔨 Funcionalidades do Projeto

- **Cadastro de Vídeos**: Permite adicionar novos vídeos com categorias personalizadas.
- **Listagem de Vídeos**: Exibição de vídeos categorizados em uma interface amigável.
- **Modal de Confirmação**: Interface para confirmação de exclusão ou edição de itens.
- **Filtro por Categoria**: Visualização de vídeos segmentados por categorias como Front-End, Back-End e Mobile.

### Exemplo Visual do Projeto

![chrome-capture-2024-12-22](https://github.com/user-attachments/assets/0c5501ab-70e8-4c0e-a559-9b10c6e08eac)

## ✔️ Técnicas e Tecnologias Utilizadas

- **React.js**: Framework para criação da interface de usuário.
- **Vite**: Ferramenta para desenvolvimento e build rápido do projeto.
- **CSS Modules**: Para estilização modular e escopo de componentes.
- **Context API**: Para gerenciar estados globais.
- **Custom Hooks**: Reaproveitamento de lógica entre componentes.

## 📁 Estrutura do Projeto

- **public/**
    - `images/`: Contém logos e ícones utilizados no projeto.
    - `index.html`: Arquivo HTML principal que é o ponto de entrada da aplicação.

- **src/**
    - **components/**: Componentes reutilizáveis como Banner, Footer, e Header.
    - **pages/**: Páginas específicas do projeto como Home e NewVideo.
    - **context/**: Definições de estados globais utilizando Context API.
    - **hooks/**: Hooks personalizados para gestão de estados e lógicas reutilizáveis.
    - **index.css**: Estilização global.
    - **main.jsx**: Arquivo de inicialização da aplicação.
    - **routes.jsx**: Configuração das rotas da aplicação.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
    - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Verifique a versão instalada com o comando:

      ```bash
      node -v
      ```
    - Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:

      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

3. **Instale as dependências**:
    - Navegue até a pasta do projeto clonado e execute o comando:

      ```bash
      npm install
      ```

4. **Inicie o projeto**:
    - Rode o comando abaixo para iniciar o servidor de desenvolvimento:

      ```bash
      npm run dev
      ```
    - Acesse o projeto pelo navegador no endereço: `http://localhost:5173`.

## 🌐 Deploy

Para fazer o deploy do projeto:

1. **Gere a build de produção**:
    - Execute o comando:

      ```bash
      npm run build
      ```

2. **Configure o ambiente de deploy**:
    - Utilize plataformas como [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), ou [GitHub Pages](https://pages.github.com/) para hospedar o projeto.

3. **Envie os arquivos para o servidor**:
    - Suba os arquivos da build para o servidor ou conecte diretamente o repositório ao serviço de deploy escolhido.

