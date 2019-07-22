# Back-end Challenge

Sua tarefa é desenvolver uma API Rest simples para um To-Do app, esse desafio tem como objetivo conhecer o seu perfil de desenvolvedor, como escreve seus códigos, como toma decisões e resolve os problemas propostos.

# Tasks
 - Desenvolver uma API Rest onde seja possível cadastrar uma nova lista de tarefas e as tarefas (tasks) contendo título, descrição e data à lista.
 - O usuário deve ter a capacidade de excluir as tarefas cadastradas em uma lista
 - O Usuário deve ter a capacidade de excluir a lista

# Ferramentas
 - Fique a vontade para utilizar qualquer linguagem server-side e framework de sua preferência (Lembrando que a maior parte de nossos projetos são em Python/Django, considere como um plus)

# Requisitos
 ### Implemente os seguintes endpoints:
  - /listas/ | Retorna um JSON com o ID de todas as listas criadas
  - /listas/{id_lista}/excluir | Recebe um JSON com o ID da lista e a exclui
  - /lista/{id_lista} | Retorna um JSON com as tasks cadastradas na lista, retornando: ID da task, Titulo e Descrição
  - /lista/{id_lista}/adicionar/ | Recebe um JSON contendo: titulo e descrição e atualiza a lista
  - /lista/{id_lista}/excluir/ | Recebe um JSON contendo o ID do item que será removido da lista

### Informações adicionais
 - Retornar as chamadas http com status code correto (200, 400, 401, 500 e etc.)
 - Retornar as tasks em ordem lógica ao que foram cadastradas pelo usuário
 - Os endpoints apresentados são exemplos, fique a vontade para altera-los se achar necessário, mas mantenha as funcionalidades requisitadas.
 - Seja criativo!

### Não requisitado
 - Você não precisa desenvolver o Front-end da aplicação, as requisições podem ser enviadas ao servidor através de ferramentas como o Postman ou similares.
 - Seu código não precisa estar pronto para produção
 - Você não precisa lidar com o cadastro de multiplas tasks na mesma requisição
 - Você não precisa lidar com autenticação

# Entrega
 - Fornecer acesso ao código/banco de dados (Preferencialmente em um repositório público no Github)
 - Fornecer um README com todas as instruções e requisitos para rodar a sua aplicação
 - Fornecer exmplos de chamadas a API
 - O prazo proposto para a entrega do desafio é de até 2 dias, a contar da data de recebimento do mesmo.

# O que será avaliado
 - Organização e qualidade do código
 - Facilidade em instalação da aplicação para avaliação
 - Decisões tomadas para resolver o desafio

Caso tenha alguma dúvida sobre o desafio proposto, poderá envia-la para o e-mail: rhenan@digicriativa.com.br
