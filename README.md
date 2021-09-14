# Projeto Microsserviço com Docker
Esta solução tem como objetovo subir executar uma stack de microsserviçoe para Rotten Potatoes.

## Clone dos repositórios
Será necessário baixar os projetos auxiliares para rodar a solução com um único comando que será descrito na sequência dos passos. </br></br>

1º Clonar este projeto para uma pasta local. No link esta o endereço do repositório [acessar repositório:](https://github.com/MarcioDeAlmeidaRosa/projeto-microservice-docker.git)</br></br>

Depois de clonado o repositório acima, acessar a pasta do repositório e clonar estes 3 repositórios dentro desta pasta. </br></br>

2º Acessar o repositório do projeto web [pelo repositório:](https://github.com/MarcioDeAlmeidaRosa/rotten-potatoes-ms) e recuperar o endereço do git para iniciar o clone.</br></br>


3º Acessar o repositório da api movie [pelo repositório:](https://github.com/MarcioDeAlmeidaRosa/movie) e recuperar o endereço do git para iniciar o clone.</br></br>


4º Por fim, acessar o último repositório da api review [pelo repositório:](https://github.com/MarcioDeAlmeidaRosa/review)</br></br>

## Executar solução
Com todos os projetos clonados em sua máquina, executar o comando abaixo para rodar a aplicação de microsserviço: </br></br>
`docker-compose up -d`</br></br>
Para acessar a aplicação, [acessar o link:](http://localhost:8066/)</br></br>

## Parar execução da solução
Rodar comando para parar a execução da solução: </br></br>
`docker-compose down`</br></br>