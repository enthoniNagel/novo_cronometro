# Iniciando com Create React App

Este projeto foi criado com [Create React App](https://github.com/facebook/create-react-app).

## Visão Geral do Projeto

Este projeto inclui uma aplicação React simples que implementa um cronômetro com funcionalidades de iniciar/pausar e resetar.

### Principais Funcionalidades

- **Botão Iniciar/Pausar**: O botão "VAI" inicia o cronômetro e, ao ser clicado novamente, pausa o cronômetro.
- **Botão Resetar**: O botão "LIMPAR" reseta o cronômetro de volta para 0.
- **Exibição Dinâmica**: O cronômetro exibe o tempo decorrido com uma precisão de uma casa decimal.

### Tecnologias Utilizadas

- **React**: Para construir a interface do usuário.
- **CSS**: Para estilizar os componentes.
- **JavaScript**: Para manipular a lógica do cronômetro e gerenciar o estado.

## Como Começar

No diretório do projeto, você pode executar:

### `npm start`

Executa a aplicação no modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-la em seu navegador.

A página será recarregada quando você fizer alterações.\
Você também pode ver quaisquer erros de lint no console.

### `npm run build`

Cria a aplicação para produção na pasta `build`.\
Ele agrupa corretamente o React em modo de produção e otimiza a construção para obter o melhor desempenho.

## Visão Geral do Código

### `App.js`

Este arquivo contém a lógica principal da aplicação, incluindo as funcionalidades de `iniciar/pausar` e `resetar`. Ele gerencia o estado do cronômetro usando `this.state` e atualiza a interface do usuário de acordo.

### `style.css`

Contém os estilos aplicados aos componentes, incluindo layout, cores e animações.

### `cronometro.png`

Uma imagem de um cronômetro que é exibida na aplicação.

## Saiba Mais

Você pode aprender mais na [documentação do Create React App](https://facebook.github.io/create-react-app/docs/getting-started).

Para aprender React, confira a [documentação do React](https://reactjs.org/).
