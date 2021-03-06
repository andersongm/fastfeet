<h2 align="center">
  Projeto Final - Bootcamp - FastFeet
</h2>

<h1 align="center">
  <img alt="Fastfeet" title="Fastfeet" src="https://github.com/andersongm/fastfeet/blob/master/.images/fastfeet-logo.png" width="200px" />
</h1>

<h3 align="center">
  Backend | Frontend | Mobile 
</h3>

#### O FastFeet é um sistema para Gestão e Entrega de Encomendas. 
A aplicação permite que um usuário autenticado possa cadastrar/gerenciar Entregadores, Destinatários e Encomendas.
O Entregador terá acesso ao aplicativo mobile para que o mesmo realize as entregas registradas para seu usuário.


### **Tecnologias Utilizadas**

### BackEnd

* NodeJS
* Docker
* Redis
* Express
* Date-Fns
* Json Web Token
* Multer
* Sequelize
* Yup
* Nodemailer
* Bcrypt
* Bee-queue


### FrontEnd

* React
* Axios
* React-Redux
* React-Router-Dom
* Redux
* Redux-Saga
* Styled-Components
* Unform

![FrontEnd](https://github.com/andersongm/fastfeet/blob/master/.images/FrontEnd_FastFeet.png)

### Mobile

* React Native
* Unform/Mobile
* Immer
* React-Navigation-5
* Styled-Components
* React-Native-Camera

![Mobile](https://github.com/andersongm/fastfeet/blob/master/.images/Mobile_FastFeet.png)


### Instalação e execução

1. Fazer o clone deste repositório

```
git clone https://github.com/andersongm/fastfeet.git
```

__Backend__
1. Crie o arquivo .env usando como exemplo o arquivo .env.example
2. Na raiz do projeto execute docker-compose up para subir os containers de DataBase e Redis
3. Na raiz do projeto execute yarn dev & yarn queue


#### Executar as Migrations
```
yarn sequelize db:migrate
```

#### Incluir Registro de Admin - Seeds
```
yarn sequelize db:seed:all
```

__Frontend__

1. Na Raiz do projeto execute yarn para baixar as libs
2. Execute yarn start para iniciar o servidor

__Mobile__

1. Na Raiz do projeto execute yarn para baixar as libs
2. Execute react-native run-ios para iniciar o Simulador do IOS

__Observação:__ O projeto foi desenvolvido com foco na utilização do IOS
