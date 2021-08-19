# basics_sql.github.io
Este repositório é para depositar comandos básicos da linguagem SQL. 

# Criar e apagar tabelas no MySQL

![image](https://user-images.githubusercontent.com/81119854/129900148-7dfe94d7-9392-4aa8-b0ca-71239912fcaa.png)

Desafio:

Criar uma tabela dentro do banco de dados SUCOS com as seguintes informações:

Nome da tabela deve ser TABELA_DE_VENDEDORES. O vendedor tem o número interno da matrícula, onde será armazenado no campo MATRICULA, que deve ser um string de 5 posições. O nome do vendedor deverá ser armazenado no campo NOME, e deve ser um string de 100 posições. Criar o campo PERCENTUAL_COMISSAO que representa quantos % de comissão o vendedor ganha sobre cada venda.

![image](https://user-images.githubusercontent.com/81119854/129902104-b8804ea7-5b24-4acb-af19-5e9f3b725af0.png)

Para apagar uma tabela, eu posso usar o assistente ou apagar por comandos:

![image](https://user-images.githubusercontent.com/81119854/129913094-09af1c9b-b8ee-4e07-a784-beabcc0610de.png)

# Inserir registros individuais em tabelas

![image](https://user-images.githubusercontent.com/81119854/129938561-2b236f29-f471-4b0c-9c34-a0929ded3871.png)

![image](https://user-images.githubusercontent.com/81119854/129940019-cb53dea9-0cef-4392-9149-4deb4579aac3.png)

# Inserir vários registros no mesmo script

![image](https://user-images.githubusercontent.com/81119854/129958006-03bb2bca-cf02-422a-9fe4-970c8d89ab19.png)

![image](https://user-images.githubusercontent.com/81119854/129958085-f0af3238-813a-4276-8ca6-080e0a058a5a.png)

![image](https://user-images.githubusercontent.com/81119854/129958921-df6ecb53-b66f-4e76-9a72-819dc4cf3c3f.png)

# Alterar registros

Vou incluir dois códigos de inserção com registros errados propositadamente:

![image](https://user-images.githubusercontent.com/81119854/129962884-96b47b8e-7a38-42c0-a008-7cec25e5b903.png)

Para alterar os registros (com base no arquivo .csv que tenho), eu faço:

![image](https://user-images.githubusercontent.com/81119854/129963012-3cb47677-4ef6-41d9-9c42-508afcb96bf2.png)

Recebemos a seguinte informação:

Cláudia Morais (00236) recebeu aumento e sua comissão passou a ser de 11%. José Geraldo da Fonseca (00233) reclamou que seu nome real é José Geraldo da Fonseca Junior. Para alterar, fazemos:

![image](https://user-images.githubusercontent.com/81119854/129963894-3a56f638-7750-4ce1-871e-bf51ceeb15df.png)

# Excluir registros

![image](https://user-images.githubusercontent.com/81119854/129982601-438ed6a0-3e07-4120-85ad-b6f50cbdf34c.png)

O vendedor José Geraldo da Fonseca Junior matrícula (00233) foi demitido. Por isso, o seu nome foi retirado:

![image](https://user-images.githubusercontent.com/81119854/129982904-ee7d7183-0691-4607-99b5-8f4b57935b81.png)

# Adicionar chave primária e manipular dados

![image](https://user-images.githubusercontent.com/81119854/129984580-0c0e9aac-8bca-42b1-8636-e63018a7e556.png)

Adição de chave primária, adição de coluna e inserção de registros:

![image](https://user-images.githubusercontent.com/81119854/129986741-2c638961-6ece-451c-bce4-cec221b3462f.png)

Exercícios:

Incluir novos campos na tabela de vendedores: data de admissão e se está ou não de férias. Além disso, adicionar uma chave primária.

![image](https://user-images.githubusercontent.com/81119854/129987962-0fe88182-ea74-452f-8ac7-5509a934a8ae.png)

Inserir registros e alterar outros já existentes:

![image](https://user-images.githubusercontent.com/81119854/129989251-9e7fe016-a973-45c4-aa1d-32353a754c9c.png)

![image](https://user-images.githubusercontent.com/81119854/129989308-94be3c82-f2dd-45f4-95d4-e0c7a3a155c3.png)

Eu posso tanto selecionar todos os campos quanto apenas campos específicos (não todos ao mesmo tempo):

![image](https://user-images.githubusercontent.com/81119854/130158114-10065734-7ed8-4f5b-b8a1-cf7bbec95f0e.png)

![image](https://user-images.githubusercontent.com/81119854/130158138-46c1f789-1378-4572-b4f1-8a3b6f3c380e.png)

Eu posso limitar o número de registros de saída utilizando 'LIMIT':

![image](https://user-images.githubusercontent.com/81119854/130158353-f501acb0-b1bc-4e42-8127-358251fdbf8f.png)

![image](https://user-images.githubusercontent.com/81119854/130158374-e0f6c1d1-45ee-4702-862d-9542ed333a95.png)

Eu posso usar um nome fantasia quando selecionar campos da minha tabela:

