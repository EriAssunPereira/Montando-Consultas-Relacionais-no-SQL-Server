# Montando-Consultas-Relacionais-no-SQL-Server
http://www.dio.me/

Para o projeto proposto, teremos que executar o arquivo **Script Filmes.sql** em seu banco de dados **SQL Server**, presente na pasta **Scripts** do repositório¹. Esse script criará um banco chamado **Filmes**, contendo as tabelas e os dados necessários para realizar o desafio.

O objetivo é criar diversas consultas que retornem os dados solicitados. Abaixo estão os pedidos e os retornos esperados:

1. **Consultar todos os filmes com seus respectivos gêneros**:
   - Retorno esperado: Uma lista de filmes com seus gêneros associados.

2. **Consultar todos os atores que participaram em pelo menos um filme**:
   - Retorno esperado: Uma lista de atores que trabalharam em algum filme.

3. **Consultar todos os filmes que possuem mais de 3 atores no elenco**:
   - Retorno esperado: Uma lista de filmes com mais de 3 atores no elenco.

4. **Consultar todos os filmes que possuem a palavra "Ação" no gênero**:
   - Retorno esperado: Uma lista de filmes com o gênero "Ação".

5. **Consultar todos os atores que participaram em filmes do gênero "Comédia"**:
   - Retorno esperado: Uma lista de atores que trabalharam em filmes de comédia.

6. **Consultar a quantidade total de filmes cadastrados**:
   - Retorno esperado: O número total de filmes no banco de dados.

7. **Consultar a quantidade total de atores cadastrados**:
   - Retorno esperado: O número total de atores no banco de dados.

8. **Consultar a média de atores por filme**:
   - Retorno esperado: A média de atores por filme.

9. **Consultar o filme com o maior número de atores no elenco**:
   - Retorno esperado: O filme com o maior número de atores.

10. **Consultar o ator que participou em mais filmes**:
    - Retorno esperado: O ator que trabalhou em mais filmes.

11. **Consultar o gênero com a maior quantidade de filmes**:
    - Retorno esperado: O gênero com mais filmes associados.

12. **Consultar o gênero com a menor quantidade de filmes**:
    - Retorno esperado: O gênero com menos filmes associados.

Para o projeto proposto, vamos precisar realizar consultas no banco de dados relacionado a um site de filmes, onde são armazenados dados sobre os filmes e seus atores. O banco de dados está modelado com as seguintes tabelas:

1. **Filmes**: Armazena informações dos filmes.
2. **Atores**: Contém informações dos atores.
3. **Gêneros**: Responsável por armazenar os gêneros dos filmes.
4. **ElencoFilme**: Representa um relacionamento do tipo muitos para muitos entre filmes e atores. Ou seja, um ator pode trabalhar em muitos filmes, e filmes podem ter muitos atores.
5. **FilmesGenero**: Representa um relacionamento do tipo muitos para muitos entre filmes e gêneros. Um filme pode ter mais de um gênero, e um gênero pode fazer parte de muitos filmes.

Agora, você deve realizar 12 consultas ao banco de dados, cada uma retornando um tipo de informação específica. Lembre-se de considerar os relacionamentos entre as tabelas e os campos relevantes para cada consulta.

https://github.com/digitalinnovationone/trilha-net-banco-de-dados-desafio
