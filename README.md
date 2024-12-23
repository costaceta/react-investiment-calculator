# Investiment Calculator com React e ViteJS

## Descrição

Este projeto é uma **Calculadora de Investimentos** desenvolvida com **React** e utilizando o **ViteJS** como ferramenta de build. O objetivo do projeto é permitir que os usuários calculem projeções financeiras com base em dados de entrada, como montante inicial, taxa de juros e período de investimento. Ideal para prática de conceitos de React, como estados, componentes e manipulação de eventos.

## Link da Aplicação

[React Investiment Calculator](https://costaceta.github.io/react-investiment-calculator/)

## Funcionalidades

- Simulação de investimento com base no valor inicial, taxa de juros e tempo.
- Possibilidade de reiniciar os cálculos sem recarregar a página.
- Interface responsiva e intuitiva.

## Tecnologias Utilizadas

- [React](https://reactjs.org/): Biblioteca para construção de interfaces de usuário.
- [ViteJS](https://vitejs.dev/): Ferramenta moderna de build para desenvolvimento rápido.
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS): Estilização da interface.

## Pré-requisitos

Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas em sua máquina:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

## Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/costaceta/react-investment-calculator.git
   ```

2. **Acesse o diretório do projeto:**

   ```bash
   cd react-investment-calculator
   ```

3. **Instale as dependências:**

   ```bash
   npm install
   # ou
   yarn install
   ```

4. **Inicie o servidor de desenvolvimento:**

   ```bash
   npm run dev
   # ou
   yarn dev
   ```

5. **Abra o jogo no navegador:**
   O Vite exibirá um link, geralmente `http://localhost:5173`. Acesse-o para utilizar a Calculadora de Investimentos.

## Estrutura do Projeto

```
├── public
│   └── investment-calculator-logo.png
├── assets
│   └── investment-calculator-logo.png
├── src
│   ├── components
│   │   ├── Header.jsx
│   │   ├── Results.jsx
│   │   └── UserInput.jsx
│   ├── App.jsx
│   ├── index.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── README.md
```

- **components/**: Contém os componentes reutilizáveis do projeto.
- **App.jsx**: Componente principal que gerencia o estado da aplicação.
- **index.css**: Arquivo de estilização.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Desenvolvido com ❤️ por [Rafael Costa](https://github.com/costaceta).
