# 🌎 Projeto TravelGo — Banco de Dados Relacional (SQL)

Este repositório contém todos os scripts SQL desenvolvidos para o projeto **TravelGo**, seguindo os requisitos da disciplina de Banco de Dados.  
O objetivo é demonstrar a criação do banco, povoamento das tabelas, consultas, atualizações e remoções utilizando comandos SQL (DDL e DML).

---

## 📌 Objetivos do Projeto

- Criar e manipular um banco de dados real no **MySQL** utilizando o **MySQL Workbench**.
- Aplicar corretamente comandos SQL das categorias **DDL** (Data Definition Language) e **DML** (Data Manipulation Language).
- Integrar o modelo lógico do projeto com scripts funcionais.
- Utilizar versionamento e compartilhamento de código via GitHub.

---

## 🛠️ Tecnologias Utilizadas

- MySQL 8+
- MySQL Workbench
- Linguagem SQL
- Git & GitHub

---

## 🧱 Estrutura do Banco de Dados

O banco **travelgo** possui as seguintes tabelas:

- **cliente** — informações pessoais dos clientes  
- **destino** — cidades e locais disponíveis para viagem  
- **viagem** — viagens realizadas pelos clientes  
- **avaliacao** — notas e comentários sobre as viagens  
- **item_reserva** — serviços adicionais (hotel, voo, seguro etc.)

Cada tabela foi criada com chaves primárias, estrangeiras e integridade referencial.

01_create_tables.sql → Criação do banco e das tabelas (DDL)
02_inserts.sql → Comandos INSERT para popular todas as tabelas
03_selects.sql → Consultas SELECT com JOIN, WHERE, ORDER BY e LIMIT
04_updates.sql → Comandos UPDATE para modificar registros
05_deletes.sql → Comandos DELETE para remover registros
README.md → Documentação do projeto


---

## 📂 Estrutura dos Arquivos do Repositório


## ▶️ Como Executar os Scripts

### **1. Criar as tabelas**
Abra o arquivo:



01_create_tables.sql


Execute tudo no MySQL Workbench.

---

### **2. Inserir dados nas tabelas**
Abra o arquivo:



02_inserts.sql


Execute para popular o banco.

---

### **3. Executar consultas avançadas**
Use o arquivo:



03_selects.sql


Aqui estão incluídos:
- JOINs  
- Filtros com WHERE  
- Ordenações com ORDER BY  
- Limitação de resultados com LIMIT  

---

### **4. Atualizar registros**
Arquivo:



04_updates.sql


Contém pelo menos **3 operações UPDATE** exigidas na atividade.

---

### **5. Deletar registros**
Arquivo:



05_deletes.sql


Contém pelo menos **3 operações DELETE** com condições.

---

## 📊 Modelo Lógico (Opcional)

Caso necessário, inclua aqui um print do DER utilizado no projeto.

Você pode colocar assim:



/images/der_travelgo.png


---

## ✔️ Requisitos da Atividade Atendidos

- [x] Criação de banco de dados  
- [x] Criação de tabelas (DDL)  
- [x] Povoamento das tabelas (INSERT)  
- [x] Consultas SQL com JOIN, WHERE, LIMIT, ORDER BY  
- [x] UPDATE e DELETE com condições  
- [x] Organização do repositório no GitHub  
- [x] README.md detalhado  

---

## 👨‍💻 Autor

**Arthur Fernando**  
Curso: *Análise e Desenvolvimento de Sistemas*  

Projeto realizado para fins acadêmicos.

---


