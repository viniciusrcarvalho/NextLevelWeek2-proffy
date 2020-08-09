<h1 align="center">
  <img width="182" alt="Proffy" src="https://user-images.githubusercontent.com/11545976/89233363-d22f3380-d5bf-11ea-8ece-a7feefc33bc4.png">
</h1>

## 👨‍🏫 Proffy | Next Level Week - 2nd Edition | 2º Edição

The purpose of the application is to propose an environment where people can register to teach classes or look for teachers. The teacher will inform the content of your specialty, the available times and the value of your hour / class.

O objetivo do aplicativo é propor um ambiente onde as pessoas possam se cadastrar para dar aulas ou procurar professores. O professor informará o conteúdo da sua especialidade, os horários disponíveis e o valor da sua hora / aula.

## 🚀 Index
- ⚙ [Tecnologies](#-tecnologies)
- 💻 [How to run](#-how-to-run)
- 📷 [Previews](#-previews)
- 🚧 [Proffy 2.0](#-proffy-2.0)

---

## ⚙ Technologies
  - **Back end**
    - NodeJS
    - Typescript
    - express
    - sqlite3
    - knex
    - cors
    - ts-node-dev
  
  - **Front end**
    - ReactJS
    - Typescript
    - react-router-dom
    - axios
  
  - **Mobile**
    - Expo
    - Typescript
    - AsyncStorage
    - axios

---

## 💻 How to run - como rodar

  > Cloning the repository
  ```bash
    # Cloning repository
    git clone https://github.com/viniciusrcarvalho/NextLevelWeek2-proffy.git
  ```

  > Running web project | Rodando o projeto web
  ```bash
    # Accessing web project | Acessando projeto web
    cd web
    
    # Running web project | Rodar o projeto
    yarn start
  ```

  > Running server | Rodar o server
  ```bash
    # Accessing server project | Acessando projeto server
    cd server

    # Run migrations to create the tables | Rodando as migrations para criar as tabelas
    yarn knex:migrate

    # Run server - Rodar o Server
    yarn start
  ```

  > Running mobile project | Rodando projeto mobile
  > You will need to download the Expo app. When the application starts, scan the qrcode with the Expo you installed.  | 
    Você precisará baixar o aplicativo Expo. Quando o aplicativo for iniciado, digitalize o qrcode com a Expo que você instalou.
  
  ```bash
    # Accessing mobile project | Acessando projeto móvel
    cd mobile

    # Change the IP in services/api.ts to connect with the back end | 
      Altere o IP em services / api.ts para se conectar ao back end
    cd services

    # Running
    yarn start
  ```

---

## 📷 Previews

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/11545976/89472198-3edc3680-d756-11ea-8d46-52db44c754a6.gif" />

  ---

  <img src="https://user-images.githubusercontent.com/11545976/89721743-a8a74b00-d9b7-11ea-9e44-7a053345f68c.gif" width="200" />
</h1>

---

## 🚧 Proffy 2.0

 - [ ] Authentication
   - [ ] Login/Logout
 - [ ] Password recovery
 - [ ] Profile management
 - [x] Splash Screen (Mobile)
 - [ ] Pagination in the list of Proffys
 - [ ] Display of available times in the list of Proffys
 - [ ] Save favorite Proffys on the database
 - [ ] Deploy
