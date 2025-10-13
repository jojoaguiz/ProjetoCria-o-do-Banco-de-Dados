# 🧮 Desafio SQL – Gerente de Banco Júnior

Olá, Gerente de Banco Júnior 👋

Este é o seu conjunto de tarefas do dia. Você deverá criar um banco de dados relacional simples e depois elaborar consultas SQL baseadas nas informações desse banco.

---

## 🧱 Exercício 1 – Criação do Banco de Dados

🧩 **Contexto:**  
Você é um gerente de bancos júnior e recebeu a seguinte tarefa do dia: criar um banco de dados para controle de pedidos de uma loja de tecnologia.

O banco de dados deverá conter **três tabelas relacionadas** entre si.

### **Requisitos**
Crie as seguintes tabelas:

- **clientes**
  - id (INTEGER PRIMARY KEY AUTOINCREMENT)
  - nome (TEXT)
  - email (TEXT)
  - telefone (TEXT)

- **produtos**
  - id (INTEGER PRIMARY KEY AUTOINCREMENT)
  - nome (TEXT)
  - preco (REAL)
  - estoque (INTEGER)

- **pedidos**
  - id (INTEGER PRIMARY KEY AUTOINCREMENT)
  - cliente_id (INTEGER, FOREIGN KEY → clientes.id)
  - produto_id (INTEGER, FOREIGN KEY → produtos.id)
  - quantidade (INTEGER)
  - total (REAL)

### **Tarefas**
1. Crie o banco de dados e as tabelas conforme os requisitos.
2. Insira pelo menos **3 clientes**, **4 produtos** e **5 pedidos** de exemplo.

---

## 🔍 Exercício 2 – Consultas SQL

🧩 **Contexto:**  
Você é um gerente de bancos júnior e recebeu a seguinte tarefa do dia: criar relatórios e consultas para auxiliar o setor financeiro.

Com base no banco criado anteriormente, elabore **7 consultas SQL** conforme os pedidos abaixo.

### **Tarefas**
1. Exibir todos os clientes cadastrados.  
2. Listar apenas o nome e preço de todos os produtos com estoque acima de 5 unidades.  
3. Mostrar todos os pedidos, incluindo o nome do cliente e o nome do produto.  
4. Calcular o total gasto por cada cliente (somando os valores dos pedidos).  
5. Atualizar o preço de um produto específico.  
6. Deletar um cliente específico e todos os seus pedidos.  
7. Mostrar quais produtos têm o menor estoque disponível.

💡 **Dica:**  
Use os comandos `SELECT`, `JOIN`, `UPDATE`, `DELETE` e `GROUP BY`.

---

🧠 **Objetivo:**  
Este desafio tem como objetivo praticar a criação de relacionamentos, inserção de dados e consultas SQL em um cenário realista de trabalho.
