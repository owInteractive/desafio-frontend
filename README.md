# Desafio Frontend OW Interactive

O desafio de Frontend foi organizado em 3 etapas, onde em cada etapa será avaliado um tipo de conhecimento diferente.

Objetivo:
Desenvolver um PWA de um Todo-list (Exemplo: https://www.w3schools.com/howto/howto_js_todolist.asp)

Premissas:
- O Web-App deverá:
- Utilizar grid responsiva
- Rodar em cima de um servidor Node
- Ter estilos escritos em SASS
- Utilizar Axios para chamadas Ajax
- Ter os componentes (botões, inputs, espaçamentos) desenvolvidos e criados por você, não será permitido o uso de Bootstrap.
- Ser desenvolvido utilizando JS Vanilla, Vue ou React, e os arquivos JS devem estar em ECMA6
- Não usar JQuery ou qualquer outro plugin
- Não usar CLI para gerar o template do seu App
- Você pode usar gerenciadores de tarefas como Gulp, para transpilar seus códigos
- A estrutura de arquivos fica a seu critério

### Etapa 1 

- Desenvolver um Web-app capaz de criar, editar, remover e ordenar os itens de um Todo-list.
- Configurações:
 Os campos para filtro/busca são:
    - Título do item
    - Status (itens aberto, concluída)
    - Prioridade (Baixa, Média e Alta)  
    
 - Os campos para cadastro de um item são:
    - Título (campo aberto, obrigatório)   
    - Descrição (campo aberto)
    - Prioridade (Select com opções: Baixa, Média e Alta)
    
- Possibilidade de Salvar e Cancelar
- Possibilidade de mudar o status do item: Aberto, Concluída
- Visualização do item deverá exibir: Título, Descrição e Prioridade

### Etapa 2 
- O Web-App deverá ser capaz de salvar os dados, (pode ser desde localStorage até o Firebase)
- Adicionar o botão de remoção
    - Ao tentar remover um item, deverá exibir um modal de confirmação para Aceitar ou Cancelar a ação.
- Os itens poderão ser ordenados, (drag and drop) e suas posições deverão ser salvas

### Etapa 3
- Desenvolver uma API para consumir e servir estes dados.
- Desenvolver todo o app em Vue.
- Desenvolver os templates usando .ejs
- Usar Express
- Componentizar partes do seu App
- HTML Semântico, Comentários nos códigos, Acessibilidade, Criar atalhos no teclado para navegação.
- Criar um painel de login e senha, para diferentes clientes usarem o seu APP. 
- Os campos para cadastro deverão ser:
  - Nome
  - E-mail
  - Senha

## Instruções:

  - Crie um fork e submeta ao github;

  - Quando terminar, envie o link do fork ou o projeto para letsrock@owinteractive.com, com o assunto [DESAFIO FRONT-END]
