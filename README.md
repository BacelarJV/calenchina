# CalenChina

Este projeto tem como objetivo implementar um calendário Chines e simular o animal respectivo do ano digitado.

## Endereço de Deploy - GitHub Pages

https://github.com/BacelarJV/calenchina

## Protótipo

https://www.figma.com/file/hKJtfDUAmheI9bx8dJq4f6/Untitled?type=design&node-id=0%3A1&mode=design&t=ryJ7KUM46CaU77O3-1

## Checklist

RA1 - Utilizar Frameworks CSS para estilização de elementos HTML e criação de layouts responsivos.
- [x] ID1 - Implementa um layout responsivo de uma página web utilizando um Framework CSS, como Bootstrap, Materialize ou Tailwind, que se adapta adequadamente a diferentes tamanhos de tela e dispositivos.
- [x] ID2 - Utiliza técnicas avançadas de CSS, como Flexbox ou Grid Layout, para criar layouts responsivos e fluidos em diferentes resoluções de tela.
- [x] ID3 - Utiliza os componentes CSS e JavaScript oferecidos por um Framework CSS, como cards, modais ou carrosséis, aplicando estilos personalizados conforme o necessário.
- [x] ID4 - Implementa um layout fluido e responsivo utilizando unidades relativas (vw, vh, %, em ou rem) em vez de unidades fixas (px) para criar uma experiência de usuário consistente em diferentes dispositivos e tamanhos de tela.
- [x] ID5 - Implementa animações em elementos da página, como hover, fadeIn/fadeOut, slideIn/slideOut, utilizando CSS Animations ou bibliotecas de animação, como o Animate.css ou JQuery, para fornecer feedback visual ao usuário e criar uma experiência interativa.
- [x] ID7 - Aplica um Design System consistente, definindo diretrizes de estilo, cores, tipografia e padrões de componentes que são seguidos em toda a aplicação, garantindo uma experiência de usuário uniforme e atraente.
- 
RA2 - Realizar tratamento de formulários e aplicar validações customizadas no lado cliente, utilizando a API do HTML e expressões regulares (REGEX).
- [x] ID 18 - Implementa tratamento de formulários no lado cliente com apresentação de mensagens de erro ou sucesso, utilizando os recursos da API do HTML, como validação de campos obrigatórios, tipo de entrada e limites de caracteres, garantindo que os dados inseridos sejam válidos antes de serem enviados para o servidor.
- [x] ID 19 - Aplica expressões regulares (REGEX) de forma eficiente para realizar validações customizadas nos campos de formulários, como formatos específicos de e-mail, telefone, data ou outros padrões personalizados definidos pelos requisitos do projeto.
- [x] ID 20 - Incorpora elementos de listagem, como checkbox, radio ou select, de maneira eficiente em formulários web, possibilitando a seleção e coleta precisa de dados pelos usuários.
- [x] ID 22 - Realiza a escrita e leitura de dados no Web Storage, permitindo a persistência de informações entre sessões de usuário e fornecendo uma maneira eficaz de armazenar dados localmente no navegador.
- 
  RA3 - Aplicar ferramentas para otimização do processo de desenvolvimento web, incluindo Node.js, NPM e linters para garantir a qualidade do código, juntamento com boas práticas de versionamento e organização de projetos.
- [x] ID8 - Configura adequadamente um ambiente de desenvolvimento usando Node.js e NPM para gerenciar pacotes e dependências do projeto, facilitando a instalação e o uso de bibliotecas e ferramentas de terceiros.
- 
RA4 - Aplicar bibliotecas de funções e componentes em JavaScript para aprimorar a interatividade de páginas web.
- [x] ID 14 - Utiliza a biblioteca jQuery para manipular o DOM e aprimorar a interatividade das páginas web, implementando funcionalidades como eventos, animações e manipulação de elementos HTML de forma eficiente. 
- [x] ID 15 - Seleciona e integra com sucesso um plugin jQuery, como o jQuery Mask Plugin ou outro plugin relevante para o projeto, a fim de melhorar a funcionalidade ou a aparência de elementos específicos em uma página web.
- 
RA5 - Efetuar requisições assíncronas para uma API fake e/ou APIs públicas, permitindo a obtenção e manipulação de dados dinamicamente.
- [x] ID 21 - Realiza requisições assíncronas para uma API fake e/ou APIs públicas, utilizando adequadamente conceitos como AJAX, Fetch API ou bibliotecas, para obter dados dinâmicos e realizar a manipulação e exibição dos resultados na página web.


  
## Manual de execução
- Clonar o repositório com `git clone`
- Fazer checkout no branch `develop` que contém as modificações mais recentes
- Abrir o projeto no editor Visual Studio Code (VS Code)
- Abrir um terminal pelo VSCode ou qualquer terminal do seu Sistema Operacional apontando para o diretório raiz do projeto 
- Instalar as dependências contidas no `package.json`
  - Comando: `npm i`
- (Opcional) Instalar o JSON Server globalmente disponível em `https://www.npmjs.com/package/json-server`
  - Comando: `npm i -g json-server` 
  - É opcional porque a dependência já vem cadastrada no arquivo `package.json` para instalação local na pasta `node_modules`
- Executar a API Fake (JSON Server) via um dos seguintes comandos: 
  - Execução via script registrado no `package.json`: `npm run json:server:routes` 
  - Ou via Execução explícita: `json-server --watch db.json --routes routes.json`
- O comando para execução do JSON Server deve ser aplicado no diretório raiz do projeto, ou seja, que contém o arquivo `db.json` e `routes.json`.
  - Por padrão, a aplicação JSON Server executa no endereço `localhost:3000`    
- Abrir um novo terminal pelo VSCode e então executar o projeto Angular
  - Comando: `ng s -o`
