<h2 align="center">
  Projeto Final - Bootcamp - FastFeet
</h2>

<h1 align="center">
  <img alt="Fastfeet" title="Fastfeet" src="https://github.com/andersongm/fastfeet/blob/master/imagens/fastfeet-logo.png" width="200px" />
</h1>

<h3 align="center">
  Fastfeet, Frontend, Mobile e Backend
</h3>

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

![FrontEnd](https://github.com/andersongm/fastfeet/blob/master/imagens/FrontEnd_FastFeet.png)

### Mobile

* React Native
* Unform/Mobile
* Immer
* React-Navigation-5
* Styled-Components
* React-Native-Camera

![Mobile](https://github.com/andersongm/fastfeet/blob/master/imagens/Mobile_FastFeet.png)


### Instalação e execução

1. Fazer o clone deste repositório

```
git clone https://github.com/andersongm/fastfeet.git
```

__Backend__
1. Crie o arquivo .env usando como exemplo o arquivo .env.example
2. Na raiz do projeto execute docker-compose up para subir os containers de DataBase e Redis
3. Na raiz do projeto execute yarn dev & yarn queue
4. Em outro terminal do VS Code execute yarn queue

#### Executar Migrations - Seeds
```
yarn sequelize db:migrate
```

#### Incluir Registros - Seeds
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
