###  
### CAKEPHP
##

##  Objetivo
    
    Como todo framework, o objetivo do cakePhp é facilitar e agilizar o desenvolvimento de sites e sistemas
    desenvolvidos com a liguagem de programação php.
    
##  Requisitos

    Os requisitos mínimos são um servidor web e uma cópia do Cake, simples assim!
    
##  Documentação
    
    A Documentação do CakePhp pode ser encontrada, nos sites http://book.cakephp.org/3.0/pt/index.html e http://api.cakephp.org/.

##  Vantagens
    
    - Utliza o padrão MVC;
    - Curva de aprendizado baixa;
    - Fácil instalação e configuração;
    - Comunidade Ativa;
    - Criação de CRUDS das tabelas(com validações embutidas), através de comandos no prompt - Cake Bake;
    - Ótima Documentação;
    - Controle de Acessos Flexível;
    - Etc...
    
##  Instalação    

Abaixo seguem os passos que utilizei para instalar o cakephp , o banco de dados e deixá-lo pronto para 
começar a trabalhar.

    1) Primeiramente realizei o download do cakephp 3.0;
    2) Feito isso, instalei o composer no windows e extraí os arquivos do cake dentro de uma pasta no meu localhost;
    3) Após ter realizado a descompactação executei o install do composer para identificar as dependências e plugins do cake;
    4) Após realizado o passo anterior, acessei a url localhost/meuProjeto, onde se localizavam os arquivos extraidos do cake, e ness página aparecia uma mensgem informando que necessitava habilitar o plugin intl do php;
    5) Fui no arquivo php.ini e habilitei o plugin intl;
    6) Realizado o passo acima, o cake ficou pronto para o uso, faltando realizar algumas configurações de banco de dados, na qual demonstrarei o que foi feito a seguir;
    
##  Configuração

Após realizar a instalação do cake e deixa-lo pronto pra uso, notei que havia na pagina principal do meu projeto uma informação sobre o banco de dados, no qual não estava configurado. Por isso, realizei os seguintes passos:
    
    1) Criei um banco de dados,no phpmyadmim do meu servidor local, com duas tabelas, apenas para dar prosseguimento aos passos de configuração;
    2) abri o arquivo config/app.php;
    3) inseri os dados de acesso ao banco de dados local criado no passo anterior;
    4) Pronto, agora o meu ambiente de trabalho está instalado e configurado, pronto para desenvolver alguma aplicação desejada;
    

## Cake Bake

    Umas das grandes vantagens de se utilizar o framework cakePhp é a ferramente Cake Bake, no qual, gera automaticamente, os controllers, os models e os templates(views) de acordo com as tabelas previamente criadas no banco de dados, além de cria CRUD's, pronto para uso, das mesmas. Para utilizar essa ferramenta é muito fácil e intuitivo, basta acessar o command, entrar na pasta corrente e digitar o seguinte comando: cake bake all [nome da tabela].

