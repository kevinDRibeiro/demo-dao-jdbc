O objetivo deste projeto é demonstrar como acessar um banco de dados com JDBC. O projeto será criado usando o Eclipse IDE, que permitirá que os usuários acessem facilmente o banco de dados.

Recursos

MySQL
JDBC
Instruções

Instale o Eclipse IDE.
Instale o MySQL.
Crie um novo projeto no Eclipse.
Adicione as seguintes dependências ao projeto:
mysql-connector-java
Implemente o código necessário para acessar o banco de dados.
Demonstrações

As seguintes demonstrações serão realizadas:

Recuperar dados
Inserir dados
Atualizar dados
Deletar dados
Transações
Padrão DAO

O padrão DAO (Data Access Object) será usado para fornecer um acesso mais abstrato ao banco de dados.

Conclusão

Ao concluir este projeto, os usuários serão capazes de acessar um banco de dados com JDBC.

Este código cria uma conexão com o banco de dados MySQL usando o driver JDBC padrão. Em seguida, cria um statement e executa uma consulta SQL para recuperar todos os registros da tabela "users". Por fim, itera sobre os resultados e imprime o nome de cada usuário.
