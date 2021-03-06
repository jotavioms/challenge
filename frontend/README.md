## Notas de Desenvolvimento

### Setup do projeto

O comando a seguir irá instalar as dependências necessárias para o projeto (*package.json*) através do NPM:

* *npm install*

### Executando o projeto

* *npm run start*
* Abra o endereço *http://localhost:8080/* no browser de sua preferência.
* Obs: projeto foi testado nos browsers *Google Chrome* e *Mozilla Firefox*.

### Adicionando um novo Chat

Para adicionar um novo chat basta incluir um novo objeto `Chat` na constante `chats`
no arquivo */src/App.js*.

### Estrutura e ferramentas utilizadas no projeto

* OOP em "ES6 modules" - facilita a legibilidade e escalabilidade da aplicação;
* Webpack - compila, minifica, e permite a utilização de módulos no JS;
* Babel - transpila o código de ES6 para ES5 permitindo maior portabilidade.
* Css e style loaders - permitem que o webpack faça o mesmo tratamento nos arquivos CSS.

### Possíveis melhorias

* Aumento do limite de caracteres na mensagem mediante formatação dos dados na tela.
* Adição de novo chat através da interface.
* Fechamento de um chat existente através da interface.
* Integração com bibliotecas de lint como o ESLint.
* Integração com bibliotecas de testes unitários como o Jasmine.
* Integração com pré-processadores CSS como o SASS.
