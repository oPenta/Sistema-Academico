🎓 Sistema de Gestão Acadêmica
Aplicação desktop para gerenciamento acadêmico desenvolvida com JavaFX, JPA/Hibernate e Maven. Permite o controle completo de cursos, professores, disciplinas e turmas, com persistência de dados em um banco de dados PostgreSQL.

✨ Funcionalidades
Painel de Controle Principal: Navegação central e intuitiva.
Gerenciamento de Cursos: CRUD (Criar, Ler, Atualizar, Deletar) completo para Cursos.
Gerenciamento de Professores: CRUD completo para Professores.
Gerenciamento de Disciplinas: CRUD completo para Disciplinas, com associação a um Curso.
Gerenciamento de Turmas: CRUD completo para Turmas, com associação a uma Disciplina e um Professor.
Interface Gráfica Moderna: Interface construída com JavaFX e FXML, com um design limpo e organizado.


🛠️ Tecnologias Utilizadas
Linguagem: Java 24
Interface Gráfica: JavaFX 17
Persistência de Dados: JPA / Hibernate 5.6
Banco de Dados: PostgreSQL
Gerenciador de Dependências: Apache Maven


📂 Estrutura do Projeto
O projeto foi organizado utilizando o padrão arquitetural MVC (Model-View-Controller) e estruturado em camadas para uma melhor organização e manutenção do código:

src/main/java/org/sysimc/
controller/: Contém a lógica de controle e os eventos da interface gráfica.
dao/: Camada de Acesso a Dados (Data Access Object), responsável pela comunicação com o banco de dados.
model/: Classes de entidade que mapeiam as tabelas do banco de dados (POJOs).
utils/: Classes utilitárias, como a JPAUtil para a configuração do Hibernate.
Main.java: Ponto de entrada da aplicação JavaFX.
src/main/resources/org/sysimc/
view/: Arquivos FXML que definem a estrutura das telas.
src/main/resources/META-INF/
persistence.xml: Arquivo de configuração da unidade de persistência do JPA/Hibernate.
