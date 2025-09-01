# FrontEnd
Projeto de iniciação ao FrontEnd Estático do bootcamp da ADA e Globotech

## Modulos 5 e 6

## Equipe 5✨(grupo 4)

-  Bernardo Soutelo
-  Iane Gomes
-  Ren Wrobleski

## Diagrama ER
O modelo utiliza três tabelas principais (Usuario, ListaTarefas, Tarefa) com relacionamentos bem definidos para garantir a integridade e normalização dos dados.

<img width="1451" height="485" alt="Diagrama SQL" src="https://github.com/user-attachments/assets/aef46c01-26db-4c20-bc83-d6740f97801f" />

### Exemplo de como ficaria a coleção listasTarefas no MongoDb

``` json
{
  "_id": ObjectId("a1b2c3d4e5f6a7b8c9d0e1f2"),
  "titulo": "Planejamento de Marketing Q4",
  "id_usuario_criador": ObjectId("67c4e9d5a4a6d1a5e7b8f2a1"),
  "id_usuario_atribuido": ObjectId("89d5a4e9a6d1e7b8f2a1c4a6"),
  "tarefas": [
    {
      "_id": ObjectId("f9e8d7c6b5a4b3c2d1e0f9a8"),
      "descricao": "Analisar resultados da campanha anterior",
      "prioridade": "alta",
      "id_usuario_atribuido": ObjectId("89d5a4e9a6d1e7b8f2a1c4a6"),
      "data_criacao": ISODate("2025-09-02T10:00:00Z"),
      "data_conclusao": null
    },
    {
      "_id": ObjectId("c1b2a3d4e5f6a7b8c9d0e1f3"),
      "descricao": "Definir orçamento para novas mídias",
      "prioridade": "media",
      "id_usuario_atribuido": ObjectId("67c4e9d5a4a6d1a5e7b8f2a1"),
      "data_criacao": ISODate("2025-09-02T10:05:00Z"),
      "data_conclusao": null
    },
    {
      "_id": ObjectId("e3f2a1b2c3d4e5f6a7b8c9d0"),
      "descricao": "Brainstorm de ideias para o Natal",
      "prioridade": "baixa",
      "id_usuario_atribuido": null,
      "data_criacao": ISODate("2025-09-02T10:10:00Z"),
      "data_conclusao": null
    }
  ]
}
```
