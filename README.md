# desafio_projeto2PBI
Desafio de Projeto da DIO de Transformação de Dados no Power BI.  

As modificações que me fizeram necessárias foram:  

1 . Modificação de valores monetários (coluna “Salary”) para valores decimais fixos e valores de horas de projeto para valor inteiro.  
2. Remoção de colunas desnecessárias.  
3. Separação da coluna “Address” dividindo a coluna por delimitador da extremidade direita (delimitador “-“) duas vezes, sendo na primeira separando o estado e na segunda separando a cidade, criando-se assim duas novas colunas, sendo a inicial “Address” se transformando em “Address.Street” e as outras duas novas sendo “Address.City” e “Address.State”.  
4. Remoção das colunas “Address.Street” e “Address.State”, pois não serão utilizadas no nosso relatório.  
5. Substituição de valor null por 0 em employee onde em Super_Ssn os employees com null são os gerentes, nesse caso houve apenas uma substituição.  
6. Mescla de employee e departments criando-se uma nova coluna onde o nome dos departamentos estão associados a cada colaborador e remoção de colunas desnecessárias.  
7. Junção de colaboradores com seus respectivos gerentes utilizando a função mescla consultas na nova tabela criada na etapa acima com a tabela employee.   
8. Mesclar colunas Fname e Lname em employees, criando apenas a coluna Name e remoção as colunas anteriores.   
9. Agrupar dados usando a função agrupar por a fim de saber quantos colaboradores existem por gerente. 

A questão sobre mesclar e não atribuir deve-se ao fato de a operação mesclar pois os assuntos são os mesmos (imagem anexada).

Após o tratamento dos dados foi realizado um relatório simples de relação dos dados, publicado no Public Service.
