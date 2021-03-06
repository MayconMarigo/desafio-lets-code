<div id="top"></div>

# Sobre o desafio

* Desenvolver um quadro kanban com as colunas "To Do", "Doing" e "Done" onde pudesse ser feito adição, remoção e alteração de tarefas e alteração de status das tarefas já adicionadas. 

-----------------------------------------------------------------------------------

# Sumário

## Rodar os projetos separados

* <a href="#back">Backend</a><br/>
* <a href="#front">Frontend</a><br/>

## Rodar os projetos com Docker
* <a href="#docker"> Docker </a><br/>

## Requisitos Funcionais

* <a href="#add-task"> Adicionar tarefas </a><br/>
* <a href="#remove-task"> Remover tarefas </a><br/>
* <a href="#update-task"> Atualizar tarefas </a><br/>
* <a href="#update-task-status"> Atualizar status das tarefas </a><br/>

## Requisitos Não Funcionais

* <a href="#column">Colunas</a>
* <a href="#counter">Contador</a>
* <a href="#markdown">Markdown</a>

## Tecnologias utilizadas

* <a href="#tech">Tecnologias</a>

-----------------------------------------------------------------------------------

# Rodando os projetos separados
* Clonar o repositório ```https://github.com/MayconMarigo/desafio-lets-code.git```.

<div id="back"></div>

## Backend
* Na pasta ```root``` do projeto rode no terminal ou na IDE ```cd back```
* Rode o comando ```npm install```
* Rode o comando ```npm run server``` para iniciar o backend.

<div id="front"></div>

## Frontend
* Na pasta ```root``` do projeto rode no terminal ou na IDE ```cd front```
* Rode o comando ```npm install```
* Rode o comando ```npm start``` para iniciar o frontend.
* O navegador abrirá automaticamente na url ```http://localhost:3000``` onde a página estará disponível.

<div id="docker"></div>

## Com Docker

* Clonar o repositório ```https://github.com/MayconMarigo/desafio-lets-code.git```.
* Na pasta ```root``` do projeto rodar o comando no gitbash ```docker-compose up```
* Após a inicialização dos containers basta navegar para a url: ```http://localhost:3000``` que a página estará disponível.

-----------------------------------------------------------------------------------

# Funcionalidades - REQUISITOS FUNCIONAIS

<div id="add-task"></div>

## Adicionar tarefa

* Ao clicar no botão com o símbolo "+" no canto inferior direito da tela abrirá uma modal solicitando as informações para adicionar uma nova tarefa.

BOTÃO:

![image](https://user-images.githubusercontent.com/67290959/167441290-f3ce2171-4543-4b65-ab4d-049fe917d47f.png)

MODAL:

![image](https://user-images.githubusercontent.com/67290959/167440603-67a2cbae-ff4d-4beb-b048-be10e387367f.png)

* É necessário preencher ambos os campos e então clicar no símbolo de confirmação no canto inferior direito da modal.

<div id="remove-task"></div>

## Remover tarefa
* Ao passar o mouse em cima de qualquer card de tarefa será liberado no canto esquerdo inferior um botão com símbolo de uma lixeira, basta clicar para excluir a tarefa desejada.

CARD: 

![image](https://user-images.githubusercontent.com/67290959/167442875-a65938df-da45-4ce9-bf01-a18a46472c63.png)

* Se a exclusão for feita com sucesso será exibido uma mensagem de confirmação no canto superior direito da tela

MENSAGEM:

![image](https://user-images.githubusercontent.com/67290959/167441134-bf29eb8f-9a96-4685-80a0-033487691c3c.png)

<div id="update-task"></div>

## Atualizar Tarefa
* Ao passar o mouse em cima de qualquer card de tarefa será liberado no canto direito inferior um botão com símbolo de uma caneta, basta clicar para editar a tarefa desejada.

CARD:

![image](https://user-images.githubusercontent.com/67290959/167442569-81f27002-5d79-47a3-be6a-28b23c914316.png)

* O card entra em modo de edição e permite que os campos sejam alterados

CARD EDITÁVEL:

![image](https://user-images.githubusercontent.com/67290959/167443137-c7401b68-7461-4a08-9227-87d203353963.png)

* É necessário preencher ambos os campos e então clicar no símbolo de confirmação no canto inferior direito do card para gravar a alteração.

<div id="update-task-status"></div>

## Alterar status
* Poderá ser alterado o status de uma tarefa das seguintes formas:
    * "To Do" para "Doing".
    * "Doing" para "To Do" ou "Doing" para "Done"
    * "Done" para "Doing"
* Para realizar a alteração basta clicar nos botões correspondentes em cada um dos cards conforme representação das setas abaixo:

![image](https://user-images.githubusercontent.com/67290959/167442205-b9877368-b8be-4414-a8f0-3d52daf02ad9.png)

-----------------------------------------------------------------------------------

# Funcionalidades - REQUISITOS NÃO FUNCIONAIS

<div id="column"></div>

## Cada uma das colunas poderá ser recolhida caso seja clicado em qualquer lugar do header da mesma:

COLUNA ABERTA (DEFAULT) : 

![image](https://user-images.githubusercontent.com/67290959/167444058-37468beb-e3a3-47f1-b3f8-44903b6e76c8.png)

COLUNA RECOLHIDA:

![image](https://user-images.githubusercontent.com/67290959/167444130-30d0c603-a560-4ba3-8528-6f06edfa70b5.png)

<div id="counter"></div>

## Contador de tarefas

* Automaticamente ao adicionar, remover ou alterar o status de uma tarefa existe um contador para saber o número de tarefas em cada uma das colunas:

COLUNAS:

![image](https://user-images.githubusercontent.com/67290959/167444603-f89f1987-f317-4995-b8f4-0d18604b65a2.png)

<div id="markdown"></div>

## Markdown

* Ao adicionar ou alterar uma tarefa poderá ser utilizado padrões de markdown que serão disponibilizados dentro do card:

EXEMPLO MARKDOWN CÓDIGO JS:

![image](https://user-images.githubusercontent.com/67290959/167471027-f448d4e6-59df-4af3-8eec-edee939fc741.png)

adicionado escrevendo:

```
~~~js
setInterval(() => {console.log("oi lets code"), 5000)
~~~
```

<div id="tech"></div>

-----------------------------------------------------------------------------------

# Tecnologias

* Docker
* React Js
    * MaterialUI / MaterialUI Icons
    * React Hooks
    * Context
* Node Js
    * Express

-----------------------------------------------------------------------------------

## <a href="#top">Clique-me para voltar ao topo da página</a>


