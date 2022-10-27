# DESAFIO DE PROCESSAMENTO DE DADOS PARA RECOMENDAÇÃO DE FILMES
1. Uma empresa de entretenimento coletou dados de clientes e suas avaliações de 
filmes disponibilizados na sua plataforma on-line. A ideia da empresa é conhecer o 
perfil de preferência dos seus usuários e consequentemente poder recomendar 
outros itens de seu catálogo. Diante desse desafio, fez-se necessário criar um 
algoritmo que possa auxiliar e indicar outros itens do catálogo analisando os 
padrões e relações entre os filmes vistos. Os analistas de Big Data decidiram 
desenvolver uma POC com os dados de filmes e usuários para encontrar a relação 
dos filmes entre os usuários.

### PASSO 1. OBTER O DATASET 
1. PARA OBTER OS DATA SET APENAS UTILIZE O WGET PARA PODER OBTER OS DADOS
2. TAMBÉM VERIFIQUEI SE OS DADOS POSSUIAM ALGUMA FALHA
3. GEREI ARQUIVOS CSV DOS DADOS
4. [O CÓDIGO ESTÁ DISPONÍVEL AQUI](https://github.com/Antonio-Borges-Rufino/Big_data_recomendacao/blob/main/get_dataset_desafio_2.ipynb)
5. [OS DADOS ESTÃO DISPONIVEIS AQUI](https://github.com/Antonio-Borges-Rufino/Big_data_recomendacao)

### PASSO 2. PROCESSAMENTO DOS DADOS
1. EM SUMA, ESSES DADOS PODERIAM SOFRER DIFERENTES TIPOS DE PROCESSAMENTO, MAS PARA ESSE DESAFIO FOQUEI APENAS EM GERAR A TABELA PARA APLICAR O ALGORITMO DE ASSOCIAÇÃO
2. OS DADOS TAMBÉM FORAM UNIDOS A PARTIR DAS ID DOS USUÁRIOS
3. O CÓDIGO ESTÁ UNIFICADO COM O CÓDIGO DO PASSO 3

### PASSO 3. APLICANDO O ALGORITMO E RESPONDENDO PERGUNTAS
1. APÓS TER OS DADOS PROCESSADOS EM TABELAS ONDE O INDEX É O ID DO USUÁRIO E AS COLUNAS SÃO OS FILMES QUE O USUÁRIO ASSISTIU, FOI-SE APLICADO O ALGORITMO APRIORI
2. O ALGORITMO FOI APLICADO PARA RESPONDER CADA PERGUNTA, EM VEZ DE GERAR UM RESULTADO E VERIFICA-LO DEPOIS
3. [AS PERGUNTAS E OS CÓDIGOS PODEM SER ACESSADOS AQUI](https://github.com/Antonio-Borges-Rufino/Big_data_recomendacao/blob/main/resp_desafio_2.ipynb)
