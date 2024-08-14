
# Meu Projeto Vue

Este projeto foi criado utilizando Vue.js e é voltado para a construção de uma aplicação de busca de receitas e refeições. A aplicação se conecta a uma API de terceiros gratuita, permitindo que os usuários busquem e explorem uma variedade de receitas e opções de refeições.

## Como criar a aplicação

Para criar a aplicação Vue, siga os passos abaixo:

1. Abra o terminal no diretório onde deseja criar o projeto.
2. Execute o seguinte comando:

   ```bash
   npm create vite@latest
   ```

   Este comando irá iniciar o processo de configuração do projeto Vue. Durante o processo, você poderá escolher Vue como o framework desejado.



## Funcionalidades da Aplicação

- **Busca de Receitas**: Os usuários podem procurar receitas com base em diferentes critérios, como ingredientes, tipo de refeição, e muito mais.
- **Exploração de Refeições**: Navegue por diversas opções de refeições oferecidas pela API, com detalhes completos sobre os ingredientes e modo de preparo.
- **API de Terceiros Gratuita**: A aplicação utiliza uma API gratuita para obter os dados das receitas e refeições, garantindo uma vasta seleção de opções para os usuários.

## Configurações
Configuração e Início do Desenvolvimento

Instale as Dependências Necessárias:

vue-router@4: Biblioteca de roteamento oficial do Vue.js para gerenciar a navegação entre páginas na sua aplicação.

   ```bash
npm install vue-router@4
 ```
vuex@4: Biblioteca oficial de gerenciamento de estado para Vue.js, que ajuda a centralizar e gerenciar o estado da sua aplicação.

   ```bash
npm install vuex@4
 ```
axios: Biblioteca de cliente HTTP baseada em Promises para fazer requisições HTTP para a API de terceiros. O -S é um atalho para --save, que adiciona a dependência ao package.json.

  ```bash
npm install axios
 ```

Configure a Porta no package.json:

Adicione ou ajuste a seção scripts no seu package.json para configurar a porta do servidor de desenvolvimento:

json
Copiar código
"scripts": {
  "dev": "vite --port 3000",
  "build": "vite build",
  "preview": "vite preview"
}
Inicie o Ambiente de Desenvolvimento:

Utilize o comando:

  ```bash
npm run dev
 ```
 
Este comando iniciará o servidor de desenvolvimento, e a aplicação estará disponível em http://localhost:3000.