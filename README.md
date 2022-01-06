# financx-backend
BackEnd do Projeto Finacx


O backend do projeto finacx, uma API Rest para armazenar os dados financeiro de uma pessoa, separando por conta e categorias. Essa API serve apenas para um estudo proprio para desenvolvimento, não sendo aconselhado a ser utilizada em um ambiente final.


Para gerar o artefato, pode executar o comando:


```shell 

mvn clean install 

```


Caso queira gerar um docker primeiro deverar setar o banco no arquivo **src/main/resources/application.properties** e depois executará os comandos: 

**Gerar imagem**


sudo docker image build -t finacx .

**Iniciar imagem**

sudo docker run -p 8080:8080 finacx


Mas para utilizar de uma forma mais completa, aconselho acessar o  [Docker-Finacx](https://github.com/geekwx/finacx-docker), que você consiguirar obter os docker de back, front, e banco. 
