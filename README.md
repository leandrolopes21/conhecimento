# Base de Conhecimento de Tecnologias

Este é um projeto simples de front-end que exibe uma coleção de linguagens de programação, frameworks e ferramentas de desenvolvimento em formato de cards. Os dados são carregados de um arquivo JSON e é possível realizar buscas para filtrar as tecnologias pelo nome.

## 🚀 Visão Geral

A página consiste em:
- Um cabeçalho com um campo de busca e botões de ação.
- Uma seção principal onde os cards com as informações das tecnologias são exibidos dinamicamente.
- Um rodapé com links externos.

## ✨ Funcionalidades

- **Carregamento Dinâmico:** As informações sobre as tecnologias são carregadas a partir do arquivo `data.json` usando a API `fetch` do JavaScript.
- **Renderização de Cards:** Para cada item no JSON, um card é criado e inserido no HTML, exibindo nome, descrição, link e tags.
- **Busca em Tempo Real:** O usuário pode digitar no campo de busca para filtrar os cards exibidos, mostrando apenas aqueles cujo nome corresponde à pesquisa.
- **Limpeza da Busca:** Um botão "Limpar" permite remover o filtro e exibir novamente todas as tecnologias.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica da página.
- **CSS3:** Estilização dos componentes, cards e layout.
- **JavaScript (Vanilla):** Manipulação do DOM, requisição de dados (fetch) e implementação da lógica de busca.
- **JSON:** Armazenamento dos dados das tecnologias.

## 📂 Estrutura de Arquivos

```
├── data.json         # Arquivo com os dados das tecnologias
├── favicon/          # Ícones da página
├── index.html        # Arquivo principal da estrutura HTML
├── script.js         # Lógica de carregamento e busca
└── style.css         # Folha de estilos
```

## 🏃 Como Executar

1. Clone este repositório.
2. Para uma experiência correta, sirva os arquivos a partir de um servidor web local. Isso é necessário porque a API `fetch` pode ter restrições de segurança (CORS) ao tentar carregar o `data.json` diretamente do sistema de arquivos (`file://`).
   - Uma maneira fácil de fazer isso é usando a extensão **Live Server** no Visual Studio Code.
3. Abra o arquivo `index.html` no seu navegador através do servidor local.

---
*Projeto criado por Leandro Lopes.*