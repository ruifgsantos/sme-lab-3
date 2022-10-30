**Universidade Lusófona de Humanidades e Tecnologias**

# Sistemas Móveis Empresariais - Laboratório 3

## Introdução

Neste laboratório iremos desenvolver uma aplicação em Flutter que permite criar, visualizar e modificar uma lista de filmes favoritos com o auxílio da tecnologia Firebase. Tal como no laboratório anterior, iremos utilizar o padrão [(BLoC)](https://bloclibrary.dev/#/) (Business Logic Component) para melhor gestão da lógica de todos os ecrãs constituintes da aplicação. Iremos introduzir também a tecnologia Firebase que nos permitirá alcançar o objetivo principal de persistência de dados numa base de dados na *Cloud*. Esta tecnologia está inserida na categoria de *BaaS (Backend As A Service)*, cuja premissa de utilização visa minimizar o *[Boilerplate](https://en.wikipedia.org/wiki/Boilerplate_code)* de criação de uma servidor capaz de responder aos pedidos de diversos clientes.

## Movies App

No final do laboratório é esperado que consigamos visualizar um ecrã de home semelhante ao da figura abaixo:


## Criação do projeto

Começemos pela criação de um projeto em Flutter com o auxílio da CLI.

~~~
flutter create sme_movies_app
~~~

Em seguida, devem abrir o Android studio na diretoria criada com a instrução acima.

## Firebase

O primeiro passo será a configuração de um projeto no Firebase. Para tal, devem aceder à [Firebase Console](https://console.firebase.google.com/) com um email de eleição vosso (gmail) e criar um projeto como demonstrada na figura abaixo:



O nome do projeto fica ao critério do aluno, sugerindo algo como **sme-movies-app**.
Nos passos seguintes devem escolher a ativação do Google Analytics e conta *Default* do Firebase.

## Configuração do Firebase

Após a criação do projeto, na página home, é possível reparar nos ícones presentes na figura abaixo:

Devem clicar no correspondente ao sistema operativo em que estão a desenvolver, Android ou iOS.

### Android


