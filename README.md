# FrontEnd
Projeto de iniciação ao FrontEnd Estático do bootcamp da ADA e Globotech

## Modulos 5 e 6
Professor **Dannyel Kayke**

## Equipe 5✨(grupo 4)

-  Bernardo Soutelo
-  Iane Gomes
-  Ren Wrobleski

## 🧠 Divisão de tarefas & Funcionalidades implementadas

### ✅ Ren Wrobleski – Tela dashboard e estilização

### ✅ Bernardo Soutelo – Tela TODO e Documentação

### ✅ Iane Gomes – Tela Login e estilização


## Diagrama ER
O modelo utiliza três tabelas principais (Usuario, ListaTarefas, Tarefa) com relacionamentos bem definidos para garantir a integridade e normalização dos dados.

<img width="1451" height="485" alt="Diagrama SQL" src="https://github.com/user-attachments/assets/aef46c01-26db-4c20-bc83-d6740f97801f" />

### Exemplo de como ficaria a coleção listasTarefas no MongoDb

``` json
{
  "_id": ObjectId("a1b2c3d4e5f6a7b8c9d0e1f2"),
  "titulo": "Projeto da API - Fase 1",
  "id_usuario_criador": ObjectId("67c4e9d5a4a6d1a5e7b8f2a1"),
  "tarefas": [
    {
      "_id": ObjectId("f9e8d7c6b5a4b3c2d1e0f9a8"),
      "descricao": "Definir endpoints de autenticação",
      "concluida": false
    },
    {
      "_id": ObjectId("c1b2a3d4e5f6a7b8c9d0e1f3"),
      "descricao": "Modelar o banco de dados de usuários",
      "concluida": true
    }
  ]
}
```
