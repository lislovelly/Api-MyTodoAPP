# Como Criei Este Sistema de Gerenciamento de Tarefas (MyTodoApp)

# MyTodoAPP

MyTodoApp é uma aplicação web construída para gerenciar tarefas pessoais de forma eficiente. Ela permite que os usuários criem, leiam, atualizem e excluam (CRUD) seus itens de tarefas com segurança, garantindo que as tarefas de cada usuário sejam privadas e acessíveis apenas a eles.

## Características
Autenticação de usuário: somente usuários autenticados podem acessar os recursos de tarefas.

Operações CRUD: os usuários podem criar, exibir, atualizar e excluir seus itens de tarefas.

Localização: O aplicativo suporta a localização em português do Brasil (pt-BR).

Design Responsivo: O aplicativo usa Bootstrap para uma interface amigável para dispositivos móveis.

## Ferramentas e Tecnologias Utilizadas
ASP.NET Core: Para construir o aplicativo Web.

Entity Framework Core: Para operações de banco de dados.

SQLite: Como o provedor de banco de dados.

Bootstrap: para design de interface do usuário responsivo.

Identidade: Para autenticação e gerenciamento de usuários.

## Uso da API
Extremidade

GET /Todo: retorna uma lista de todos os itens de tarefas para o usuário autenticado.

GET /Todo/Details/{id}: retorna detalhes de um item de tarefa específico.

GET /Todo/Create: retorna a página para criar um novo item de tarefa.

POST /Todo/Create: Cria um novo item de tarefa.

GET /Todo/Edit/{id}: retorna a página para editar um item de tarefa existente.

POST /Todo/Edit/{id}: atualiza um item de tarefa existente.

GET /Todo/Delete/{id}: retorna a página para confirmar a exclusão de um item de tarefa pendente.

POST /Todo/Delete/{id}: exclui um item de tarefa pendente.

## Exemplo de uso
Para criar um novo item de tarefa:

Fazer o Registro

Clicar em Create New

Preencher o formulário: Forneça o título e marque se for feito.

Enviar o formulário: O item será criado e salvo no banco de dados.

## Desafios
Manipulando a autenticação do usuário
Garantir que apenas usuários autenticados possam acessar e manipular seus itens de tarefas necessárias ASP.NET integração com a identidade principal e a implementação de verificações de autorização adequadas no aplicativo.

## Gerenciamento de Banco de Dados
O uso do Entity Framework Core com SQLite envolveu o gerenciamento de migrações e a garantia de que as operações de banco de dados fossem eficientes e seguras.

## Localização
A implementação do suporte à localização para o português do Brasil exigiu a configuração do middleware de localização de solicitações e a garantia de que todo o texto voltado para o usuário fosse traduzível.

## Conclusão
MyTodoApp é um aplicativo para gerenciar tarefas pessoais. Ele mostra habilidades essenciais no desenvolvimento ASP.NET Core, incluindo autenticação de usuário, operações CRUD e design responsivo. 

Home
![Screenshot_3](https://github.com/lislovelly/Api-MyTodoAPP/assets/135989808/4908b391-b0be-49c9-bec6-10f5e2a079e3)

Login
![Screenshot_4](https://github.com/lislovelly/Api-MyTodoAPP/assets/135989808/e0c9c5ae-2f02-4f31-a50e-05317b7c38b9)

Tarefa criada
![Screenshot_1](https://github.com/lislovelly/Api-MyTodoAPP/assets/135989808/d3515a04-6789-41ac-bf17-3998cdcc5242)

Detalhes tarefa
![Screenshot_2](https://github.com/lislovelly/Api-MyTodoAPP/assets/135989808/d4e39a80-f8ef-43c3-b6d5-cacf8c5d7c43)


