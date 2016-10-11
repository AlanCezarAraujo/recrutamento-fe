# Desafio Front-End da Concrete Solutions

## Proposta  
Implementar uma aplicação client-side, que consulte a [API do GitHub](https://developer.github.com/v3/) e mostre os repositórios mais populares de um determinado usuário. Esta aplicação deve funcionar nos navegadores mais recentes do mercado.

## Requisitos

* Eu, como usuário, desejo buscar por um usuário do GitHub;
* Eu, como usuário, desejo ver os detalhes desse usuário que foi buscado (número de seguidores, número de seguidos, imagem do avatar, e-mail e bio);
* Eu, como usuário, desejo ver a listagem dos repositórios desse usuário que foi buscado, ordenados pelo número decrescente de estrelas;
* Eu, como usuário, desejo poder alterar a ordem da listagem de repositórios;
* Eu, como usuário, desejo ver uma página com os detalhes de um repositório (nome, descrição, ,número de estrelas, linguagem e um link externo para a página do repositório no GitHub), que pode ser clicado na listagem dos repositórios;

### Rotas da aplicação

* **'/':** Tela para pesquisar usuários
* **'/:user_name':** Tela com detalhes de um usuário selecionado
* **'/:repo_name':** Tela com detalhes de um repositório selecionado

## Definição de Pronto

* É necessário o uso de um framework JavaScript, de preferência [React.js](https://facebook.github.io/react/) ou [Angular](https://angular.io/).
* Não é obrigatório mas recomendado que sua aplicação esteja coberta com testes (unitários ou funcionais), e que exista um relatório de cobertura de testes.
* É desejável o uso de algum pré-processador de CSS como PostCSS, SASS, LESS ou Stylus.
* É desejável o uso de alguma arquitetura CSS como SMACCSS, BEM ou Atomic Design.
* É obrigatório que o layout seja facilmente acessível com HTML Semântico, navegação via teclado e responsivo para dispositivos com a resolução mínima de 320 x 480;
* Não é obrigatório mas recomendamos o uso de algum *task runner* como [Grunt](http://gruntjs.com/) ou [Gulp](http://gulpjs.com/);
* É obrigatório um arquivo README.md com instruções para instalação de dependências e execução do projeto e testes;

As APIs a serem consumidas são:
* Detalhes de um usuário: [https://api.github.com/users/{username}](https://api.github.com/users/{username})
* Repositórios de um usuário: [https://api.github.com/users/{username}/repos](https://api.github.com/users/{username}/repos)
* Detalhes de um repositório: [https://api.github.com/repos/{full_name}](https://api.github.com/repos/{full_name})

### Processo de submissão

O desafio deve ser entregue pelo [GitHub](http://github.com/) e a aplicação deve estar hospedada ([Heroku](https://www.heroku.com/), [Firebase](https://www.firebase.com/), [Plunker](https://plnkr.co/), etc).  
As URLs devem ser enviadas por email.

Qualquer dúvida em relação ao desafio, responderemos por e-mail.

Bom trabalho!
