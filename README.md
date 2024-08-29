# ETL completo para acessar dados de um site e processa-los para atender requisitos empresariais.

O objetivo é criar um script automatizado que pode extrair a lista de todos os países em ordem de seus PIBS em bilhoes de USDs(arredondando para 2 casas decimais) conforme registardo pelo Fundo Monetário Internacional (FMI). Como o FMI divulga essa avaliacao duas vezes por ano, esse codigo sera usado pela organização para extrair as informações conforme elas forem atualizadas.

os dados disponíveis estao na URL abaixo:



-  As informações precisam ser disponiveis como **CSV**
-  Como uma Tabela em um arquivo de banco de dados com atributos **country** e **GDP_USD_billion**
-  Registar  um arquivo com todo o processo de execução em um arquivo **.txt**
  

## Objetivo do projeto:

  1. Escrever uma função de Extração de dados para recuperar as informações relevantes da URL necessária.
  2. Transforme as informações disponíveis do PIB em 'Bilhões de USD' de 'Milhões de USD'.
  3. Carregue as informações transformadas no arquivo CSV necessário e como um arquivo de banco de dados.
  4. Execute a consulta necessária no banco de dados.
  5. Registre o progresso do código com registros de data e hora apropriados.




