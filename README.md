# Java JDBC - Gestão de Cursos

Aplicação de console desenvolvida em Java com persistência de dados no banco PostgreSQL via JDBC. O sistema oferece um menu interativo com switch-case que permite realizar todas as operações de CRUD na tabela de cursos: cadastrar novo curso, listar todos os registros, atualizar dados existentes e excluir itens por meio do identificador (ID).

Para executar o projeto, basta rodar o script SQL de criação da tabela `tb_curso` no PostgreSQL local, ajustar as credenciais de acesso no arquivo `Banco.java` e executar a classe `Main.java` diretamente pelo IntelliJ IDEA com o driver JDBC devidamente configurado.
