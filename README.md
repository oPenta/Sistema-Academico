# 🎓 Sistema de Gestão Acadêmica

![Java](https://img.shields.io/badge/Java-24+-blue?style=for-the-badge&logo=java)
![JavaFX](https://img.shields.io/badge/JavaFX-17-orange?style=for-the-badge&logo=openjfx)
![Hibernate](https://img.shields.io/badge/Hibernate-5.6-red?style=for-the-badge&logo=hibernate)
![Maven](https://img.shields.io/badge/Maven-3-lightgrey?style=for-the-badge&logo=apache-maven)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14-blue?style=for-the-badge&logo=postgresql)

Aplicação desktop para gerenciamento acadêmico desenvolvida com JavaFX, JPA/Hibernate e Maven. Permite o controle completo de cursos, professores, disciplinas e turmas, com persistência de dados em um banco de dados PostgreSQL.

---

## ✨ Funcionalidades

* **Painel de Controle Principal:** Navegação central e intuitiva com botões grandes.
* **Gerenciamento de Cursos:** CRUD (Criar, Ler, Atualizar, Deletar) completo para Cursos.
* **Gerenciamento de Professores:** CRUD completo para Professores.
* **Gerenciamento de Disciplinas:** CRUD completo para Disciplinas, com associação a um Curso.
* **Gerenciamento de Turmas:** CRUD completo para Turmas, com associação a uma Disciplina e um Professor.
* **Interface Gráfica Moderna:** Interface construída com JavaFX e FXML, com um design limpo e organizado.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java 11+
* **Interface Gráfica:** JavaFX 17
* **Persistência de Dados:** JPA / Hibernate 5.6
* **Banco de Dados:** PostgreSQL
* **Gerenciador de Dependências:** Apache Maven

---

## 📂 Estrutura do Projeto

O projeto segue o padrão arquitetural **MVC (Model-View-Controller)**, organizado em camadas para melhor manutenção e organização do código:

src
├── main
│   ├── java
│   │   └── org
│   │       └── sysimc
│   │           ├── controller/  # Lógica de controle e eventos
│   │           ├── dao/         # Comunicação com o banco de dados
│   │           ├── model/       # Classes de entidade (POJOs)
│   │           ├── utils/       # Classes utilitárias (JPAUtil)
│   │           └── Main.java    # Ponto de entrada da aplicação
│   │
│   └── resources
│       ├── META-INF
│       │   └── persistence.xml  # Configuração do Hibernate/JPA
│       └── org
│           └── sysimc
│               └── view/        # Arquivos FXML (telas)
│
└── pom.xml                      # Arquivo de configuração do Maven

