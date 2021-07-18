# Módulo 07 - React

- Por que React?
- O que é:

  - Lib para a criação de intefaces;
  - Utilizada para a construção de SPA (Single Page Applications);
  - Podemos chamar de framework, devido a seu ecossistema;
    - ReactJS
    - React Native
    - Redux
    - Webpack
    - Etc...
  - Tudo fica dentro do JavaScript (elementos visuais, lógica e estilo);

- Vantagens:

  - Organização do código:
    - Dividir nosso app/código em blocos especifícos;
    - O funcionamento de um componente não interfere em outro;
    - Se um componente é removido, o resto continua funcionando;
  - Divisão de responsabilidades:
    - Back-end: Regras de negócio
    - Front-end: interface
  - Programação declarativa
    - Dizemos ao código o que queremos, ele se encarrega do resto;

- Preparando o ambiente
- Fundamentos do React
- Consumindo dados de uma API
- Instalando e configurando react-router-dom
- Importando as rotas no componente App
- Organização, boas práticas e componentes de estilo
- Salvando dados no Storage
- Renderizando repositórios e programação declarativa
- Link react-router-dom
- Tratamento de erros e use History
- Conditional rendering
- Daqui pra frente e encerramento

## Para se aprofundar:

### React Context API

- API do próprio React para lidar com estados muito complexos;
- Cria contextos para compartilhamento de dados (estado);
- Corrige muito bem o problema de prop drilling: quando você passa a mesma para propriedade para muitos compnents filhos;

### Redux

- Cria um estado global, que serpa acessado por toda a aplicação;
- Lida muito bem com estados muito complexos e side effects (quando um evento ocorre por causa de uma ação do usuário ou da própria aplicação);

Context API ou Redux?

Context API contextos especificos;
Redux cria um contexto global;
Context API é um hook do próprio React;
Redux é um pacote à parte, podendo ser usado com Angular, Vue, etc;
Redux lida com estado e Side Effects;
Context API lida somente com estado;

Conclusão: Se sua aplicação precisa de uma gestão complexa de estado e precisa lidar com muitas ações acontecendo em diferentes partes do aplicativo, use Redux; se você precisa lidar com o compartilhamento de dados entre componentes e evitar prop drilling, Context API;

### Gatsby.js

- Framework baseado em React;
- Tem todo um ecossistema já preparado para garantir o máximo de produtividade pro desenvolvedor;
- integração com GraphQL;
- Você desenvolve com React e ele te devolve uma página estática (diferente de CMS's como Worldpress, que gera um site dinâmico);

### Next.js

- Framework open source, mantida pela Zeit;
- Visa facilitar e padronizar o desenvolvimento de aplicações React;
- Possui ferramentas que lidam com problemas referentes a SEO, com suporte a SSR (server side rendering);
