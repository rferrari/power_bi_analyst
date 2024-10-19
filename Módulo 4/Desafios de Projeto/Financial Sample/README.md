# Processo de Construção do Diagrama

O objetivo do presente projeto é criar um modelo de base de dados estrela (star schema) a partir da tabela "Financial Sample" usando DAX (Data Analysis Expressions). O modelo será composto por sete tabelas: quatro tabelas dimensão (D_Produtos, D_Produtos_Detalhes, D_Descontos, D_Detalhes) e três tabelas fato (F_Vendas, D_Calendário).

A construção do modelo seguirá as seguintes etapas:

- Seleção das colunas da tabela original para cada tabela dimensão.
- Criação das tabelas dimensão baseadas nas seleções realizadas.
- Seleção das colunas da tabela original para as tabelas fato.
- Criação das tabelas fato.
- Reorganização das colunas para uma melhor visualização e compreensão da informação.

Funções DAX Utilizadas

Foi utilizada *Calendar()* para criar a tabela D_Calendário.
