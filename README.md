🎓 Sistema de Gestão Acadêmica
Aplicação desktop para gerenciamento acadêmico desenvolvida com JavaFX, JPA/Hibernate e Maven. Permite o controle completo de cursos, professores, disciplinas e turmas, com persistência de dados em um banco de dados PostgreSQL.

✨ Funcionalidades
Painel de Controle Principal: Navegação central e intuitiva.
Gerenciamento de Cursos: CRUD (Criar, Ler, Atualizar, Deletar) completo para cursos.
Gerenciamento de Professores: CRUD completo para professores.
Gerenciamento de Disciplinas: CRUD completo para disciplinas, com associação a um curso.
Gerenciamento de Turmas: CRUD completo para turmas, com associação a uma disciplina e um professor.
Interface Gráfica Moderna: Interface construída com JavaFX e FXML, com design limpo e organizado.
🛠️ Tecnologias Utilizadas
Linguagem: Java 24
Interface Gráfica: JavaFX 17
Persistência de Dados: JPA / Hibernate 5.6
Banco de Dados: PostgreSQL
Gerenciador de Dependências: Apache Maven
📂 Estrutura do Projeto
O projeto segue o padrão arquitetural MVC (Model-View-Controller), organizado em camadas para melhor manutenção e organização do código:

src/main/java/org/sysimc/
│
├── controller/   # Lógica de controle e eventos da interface gráfica
├── dao/          # Camada de acesso a dados (Data Access Object), comunicação com o banco de dados
├── model/        # Classes de entidade (POJOs) que mapeiam as tabelas do banco de dados
├── utils/        # Classes utilitárias, como JPAUtil para configuração do Hibernate
└── Main.java     # Ponto de entrada da aplicação JavaFX

src/main/resources/org/sysimc/
└── view/         # Arquivos FXML que definem a estrutura das telas

src/main/resources/META-INF/
└── persistence.xml   # Arquivo de configuração da unidade de persistência do JPA/Hibernate
