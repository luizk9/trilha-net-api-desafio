# DIO - Trilha .NET - API e Entity Framework
www.dio.me

## Desafio de projeto
 - no intuito de cumprir as etapas foram execultados os metodos do controlle:<br>
1- ObterPorId(int id);<br>
2- Obtertodos();<br>
3- ObterPorTitulo(string titulo);<br>
4- ObterPorData(DateTime data);<br>
5- ObterPorStatus(EnumStatusTarefa status);<br>
6- Criar(Tarefa tarefa);<br>
7- Atualizar(int id, Tarefa tarefa);<br>
8- Deletar(int id);<br>

9 - foi criado a pasta Migrations e seus arquivos com o 
comando  dotnet -ef migrations add
 
 Observação esta pasta não foi subida para o GITHUB
 
 - Desta feita todas os demais verbos do swagger a baixo estão rodando normalmente
 
 

====================================================


**Swagger**


![Métodos Swagger](swagger.png)


**Endpoints**


| Verbo  | Endpoint                | Parâmetro | Body          |
|--------|-------------------------|-----------|---------------|
| GET    | /Tarefa/{id}            | id        | N/A           |
| PUT    | /Tarefa/{id}            | id        | Schema Tarefa |
| DELETE | /Tarefa/{id}            | id        | N/A           |
| GET    | /Tarefa/ObterTodos      | N/A       | N/A           |
| GET    | /Tarefa/ObterPorTitulo  | titulo    | N/A           |
| GET    | /Tarefa/ObterPorData    | data      | N/A           |
| GET    | /Tarefa/ObterPorStatus  | status    | N/A           |
| POST   | /Tarefa                 | N/A       | Schema Tarefa |

