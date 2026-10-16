# MovieCity - Landing Page 🎬

Uma landing page responsiva de um serviço de streaming fictício, construída com **React + Vite**. 

O objetivo principal deste projeto é servir como um exercício prático de componentização no React, estilização com CSS puro e adaptação de layout para diferentes tamanhos de tela (responsividade), sem depender de bibliotecas de UI externas.

## 🚀 Tecnologias Utilizadas

Este projeto foi desenvolvido com as seguintes tecnologias:

*   **[React 19](https://react.dev/)**: Biblioteca de UI baseada em componentes.
*   **[Vite 7](https://vitejs.dev/)**: Servidor de desenvolvimento rápido com HMR e bundler de produção.
*   **JavaScript (ESM)**: Linguagem e sistema de módulos.
*   **CSS Puro**: Estilização global e responsividade (media queries) feitas do zero. Nenhuma biblioteca como Tailwind ou Bootstrap foi utilizada.
*   **ESLint**: Padronização e análise estática do código.

## 🎯 O que o projeto faz

A página é dividida em duas áreas principais:
1.  **Header (Cabeçalho)**: Contém a logo "MovieCity", um menu de navegação e um botão de Login. Em dispositivos móveis, transforma-se em um menu hambúrguer animado apenas com CSS.
2.  **Main (Conteúdo Principal)**: Apresenta um texto de chamada e um grid interativo com 6 cards de filmes em destaque. 

O layout é **100% responsivo**, adaptando-se de forma fluida a desktops, tablets e celulares.

## 📋 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:
*   [Node.js](https://nodejs.org/en/) (versão 20.19+ ou 22.12+)
*   npm, yarn ou pnpm

## 🔧 Como executar o projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   ```

2. **Entre na pasta do projeto:**
   ```bash
   cd 01_landinpage
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   ```
   *O projeto estará disponível em `http://localhost:5173`.*

## 📦 Scripts Disponíveis

*   `npm run dev`: Inicia o servidor local com HMR.
*   `npm run build`: Gera a versão otimizada de produção na pasta `dist/`.
*   `npm run preview`: Serve localmente o build da pasta `dist/` para testes antes do deploy.
*   `npm run lint`: Roda o ESLint para verificar a padronização do código.

## 📁 Estrutura de Pastas Principal

```text
src/
 ├── assets/          # Imagens utilizadas nos cards
 ├── components/      # Componentes React
 │   ├── Header.jsx   # Cabeçalho e navegação mobile
 │   ├── Main.jsx     # Conteúdo principal e grid de filmes
 │   └── Home.jsx     # Container unificando a página
 ├── App.jsx          # Componente raiz
 ├── index.css        # Estilos globais e media queries
 └── main.jsx         # Ponto de entrada da aplicação
```

## 💡 Próximos Passos / Ideias de Melhoria

*   Melhorar a acessibilidade trocando as divs dos cards por `<button>`.
*   Adicionar título e informações adicionais nos cards dos filmes.
*   Integrar com uma API real (como a do TMDB) para renderizar os filmes dinamicamente.
*   Implementar um carrossel horizontal para a versão mobile.
*   Adicionar suporte a `prefers-reduced-motion` para usuários que preferem menos animações.
