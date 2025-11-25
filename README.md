# 📚 CRUD Escola — Sistema de Cadastro de Alunos

Este projeto é uma aplicação Windows Forms desenvolvida em **C# (.NET Framework)** com o objetivo de cadastrar, consultar, atualizar e excluir alunos de uma base de dados.
O sistema foi pensado para ser simples, intuitivo e funcional para uso em escolas ou cursos.

---

## ✨ Funcionalidades

✔️ **Cadastrar Aluno**  
✔️ **Pesquisar Aluno**  
✔️ **Atualizar Dados do Aluno**  
✔️ **Excluir Aluno**  
✔️ **Exibir registros em uma tabela (DataGridView)**  
✔️ Interface gráfica amigável e organizada

---

## 🧑‍💻 Tecnologias Utilizadas

- **C# (Windows Forms)**
- **.NET Framework**
- **SQL Server**
- **Visual Studio**

---

## 🖼️ Interface do Sistema

A tela principal permite inserir e visualizar informações do aluno como:

- Número de matrícula
- Nome
- Idade
- Turno (Manhã/Tarde)
- Série (1º, 2º ou 3º)
- Unidade (Barroca/Floresta)
- Turma (combo box)

Além disso, conta com botões:

- **Cadastrar**
- **Pesquisar**
- **Atualizar**
- **Deletar**
- **Sair**

---

## 📦 Estrutura do Projeto

```
CRUD_Escola/
├── Conexao.cs           # Classe de conexão com o banco
├── Aluno.cs             # Classe modelo do aluno
├── Alunos.cs            # Tela CRUD de alunos
├── Form1.cs             # Menu principal
├── Professor.cs         # Classe modelo (se aplicável)
├── Professores.cs       # CRUD (se aplicável)
├── App.config
└── Program.cs
```

---

## 🗄️ Banco de Dados

Tabela recomendada:

**Alunos**
| Campo   | Tipo | Descrição |
|--------|------|----------|
| id | INT PRIMARY KEY auto_increment | Identificador |
| nome | VARCHAR | Nome do aluno |
| idade | INT | Idade |
| turno | VARCHAR | Manhã/Tarde |
| serie | INT | Série (1,2,3) |
| unidade | VARCHAR | Barroca/Floresta |
| turma | VARCHAR | Turma |
