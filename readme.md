# Entrega do Projeto Final da Trilha 4 do Programa Descodificadas

## Projeto Escolhido: Lista de Tarefas com Tema 80's

### Descrição
Este projeto tem por objetivo aprender os fundamentos do desenvolvimento web através de mentorias e atividades práticas, auxiliando no aprendizado de novas ferramentas como:
- Editores de códigos
- Linguagem de marcação HTML
- Estilização CSS
- Programação JavaScript
- Banco de Dados
- Uso de APIs
- Servidores
- Protocolos
- Frameworks

---

## 1. Público-Alvo
A Lista de Tarefas foi a escolha para a entrega final, pois é uma ferramenta simples e eficaz, ideal para:
- Estudantes
- Profissionais
- Qualquer pessoa que busque organizar suas atividades diárias

Ela permite registrar, acompanhar e priorizar tarefas, garantindo maior foco e produtividade.

### Benefícios
- **Evitar esquecimentos**
- **Otimizar o tempo** ao organizar tarefas por ordem de importância
- **Melhorar o planejamento** ao visualizar compromissos em um só lugar
- **Proporcionar sensação de realização** ao concluir atividades

É uma solução prática e eficiente para gerenciar rotinas pessoais e profissionais.

---

## 2. Interface do Usuário
O projeto desenvolvido é uma aplicação simples e funcional que permite ao usuário:
- Adicionar, visualizar e gerenciar atividades

### Funcionalidades
- Exibição das tarefas em uma tabela organizada, com informações como:
  - Data de criação
  - Status (pendente, em andamento ou concluída)
  - Botões de ação para edição e exclusão

O design do projeto é inspirado nas cores neon e vibrantes dos anos 80, trazendo uma estética retrô com um toque moderno. É totalmente responsivo, garantindo uma experiência visual marcante e confortável em diferentes dispositivos.

---

## 3. Base de Dados e Tecnologias Utilizadas

- **VS Code (Visual Studio Code):**
  Um editor de scripts multiplataforma da Microsoft. [Learn Microsoft](https://learn.microsoft.com/pt-br/powershell/scripting/dev-cross-plat/vscode/using-vscode?view=powershell-7.4)

- **Node.js:**
  Ambiente de execução de JavaScript para criar servidores e aplicativos. [Node.js](https://nodejs.org/pt)

- **Nodemon:**
  Ferramenta para reiniciar automaticamente o aplicativo Node.js ao detectar alterações. [npmjs](https://www.npmjs.com/package/nodemon)
  ```bash
  # Instalação:
  npm i nodemon
  ```
  - Comando para iniciar o Nodemon server: `npm run dev`
  - Comando para iniciar o backend: `npm start`
  - Finalizar: pressione `CTRL + C`

- **Express:**
  Framework minimalista para aplicativos web no Node.js. [Expressjs](https://expressjs.com/)
  ```bash
  # Instalação:
  npm install express
  ```

- **Cors:**
  Middleware para habilitar CORS em aplicativos. [npmjs](https://www.npmjs.com/package/cors)
  ```bash
  # Instalação:
  npm install cors
  ```

- **dotenv:**
  Carrega variáveis de ambiente de um arquivo `.env`. [npmjs](https://www.npmjs.com/package/dotenv)
  ```bash
  # Instalação:
  npm install dotenv --save
  ```

- **MySQL:**
  Sistema de gerenciamento de banco de dados relacional. [OCI](https://www.oracle.com/mysql/what-is-mysql/)

- **Docker:**
  Plataforma para desenvolver, enviar e executar aplicativos. [Docker](https://docs.docker.com/get-started/docker-overview/)
  ```bash
  # Instalação da imagem MySQL:
  docker run --name mysql -e MYSQL_ROOT_PASSWORD=root -p 3306:3306 -d mysql
  ```

- **JSON:**
  Formato padrão para representar dados estruturados. [Developer Mozilla](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)

- **HTML (Linguagem de Marcação de HiperTexto):**
  Define o significado e a estrutura do conteúdo da web. [Developer Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/HTML)

- **CSS (Cascading Style Sheets):**
  Linguagem para descrever a apresentação de documentos HTML. [Developer Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

- **JavaScript:**
  Linguagem de script leve e baseada em objetos. [Developer Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

---

## 4. API

- **Insomnia:**
  Cliente de API para envio de requisições. [Insomnia](https://docs.insomnia.rest/insomnia/send-your-first-request)

### Endpoints
- **/tasks:** Criar e listar as tarefas
- **/tasks/{id}:** Manipular as tarefas

### Métodos Suportados
- **GET:** Retorna as informações da API
- **POST:** Envia os dados inseridos e retorna uma confirmação
- **PUT:** Atualiza os dados modificando uma tarefa existente
- **DELETE:** Exclui uma tarefa

---

**Nota:** Este projeto representa o culminar do aprendizado na Trilha 4 do Programa Descodificadas, unindo criatividade e habilidades técnicas adquiridas ao longo da jornada.
