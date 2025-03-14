#COMANDOS GCLOUD
###versão do gcloud
gcloud -v
###loga no gcloud
gcloud auth login
###inicializa o gcloud
gcloud init

#GIT
##versão do git
git -v 
##ajuda do git
git -h 
##clona um repositório
git clone [link] 
##status do repositório
git status 
##adiciona todos os arquivos
git add . 
##commita os arquivos
git commit -m "mensagem" 
##envia os arquivos para o repositório
git push 
##atualiza os arquivos do repositório
git pull 

#MAVEN
##versão do maven
mvn -version 
##limpa o projeto
mvn clean 
##roda os testes do projeto (testes unitários)
mvn test 
##verifica o projeto
mvn verify 
##gera o site do projeto
mvn site 
##compila o projeto
mvn compile
##empacota o projeto
mvn package 
##instala o projeto
mvn install 
##faz o deploy do projeto
mvn appengine:deploy 
##roda o projeto
mvn appengine:run
##COMANDO USADO PARA CORRER O PROJETO LOCALMENTE
##empacota e roda o projeto
mvn package appengine:run 
