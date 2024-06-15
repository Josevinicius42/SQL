# SQL <img src="https://github.com/Josevinicius42/SQL/assets/144733214/2a4cd52e-c5d2-4ebf-918b-bb9d749de60c" alt="sql" width="60"/>

Repositório de estudos dos códigos SQL mais utilizados de junção de tabelas **Inner Join** , **Left Join**, **Right Join** e **Full Join**


## Inner Join

  Esse metodo é utilizado para combinar duas tabelas que tenham uma condição em relação entre elas.

    SELECT *
    FROM A
    INNER JOIN B ON A.key = B.key

**OBS: Juntar a tabela A com a tabela B pela coluna "key"**

Codigo Explicado:

    SELECT colunas
    FROM tabela1
    INNER JOIN tabela2 ON condição_de_junção;
    
![img_inner_join](https://github.com/Josevinicius42/SQL/assets/144733214/83a40a7a-9929-436c-9d96-3d8a191d822d)

## Left Join

  Metodo que retorna as linhas da tabela da ESQUERDA

    SELECT *
    FROM A
    LEFT JOIN B ON A.key = B.key;

**OBS: Juntar a tabela atual com a tabela da ESQUERDA**

Codigo Explicado:

    SELECT colunas
    FROM tabela1
    LEFT JOIN tabela2 ON condição_de_junção;
    
![img_left_join](https://github.com/Josevinicius42/SQL/assets/144733214/e0425973-81d9-46a8-bbd2-d7e4c81b65b3)



