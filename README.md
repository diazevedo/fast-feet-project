<h1> FastFeet </h1>

Repository containing backend, frontend and mobile of the final challenge from the Bootcamp Rockseat :rocket:.


<p align="center"><img src=".github/fastfeet-logo.png"/></p>

# :page_with_curl: About

<p>This is an application for a fictional operator. The back-end was made with Node.JS, Frontend Web with ReactJS and mobile with React Native. The web part of this application is designed for administrators to manage recipients, mails, see problems and more. The post office can access the application through the mobile version of the application. The following technologies were used in this app: </p>

<ul>
  <a href="https://classic.yarnpkg.com/pt-BR/package/express"><li>ExpressJS</li></a>
  <a href="https://sentry.io/organizations/ilgssonbraga/issues/"><li>Sentry</li></a>
  <a href="https://github.com/bee-queue/bee-queue"><li>Bee Queue</li></a>
  <a href="https://mailtrap.io/"><li>Mailtrap</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/redis"><li>Redis</li></a>
  <a href="https://www.docker.com/"><li>Docker</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/jsonwebtoken"><li>JSON Web Token</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/multer"><li>Multer</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/sequelize"><li>Postgres with Sequelize</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/yup"><li>Yup</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/axios"><li>Axios</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/immer"><li>Immer</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/redux"><li>Redux</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/redux-saga"><li>Redux Saga</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/reactotron-react-js"><li>Reactotron</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/prop-types"><li>Prop Types</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/styled-components"><li>Styled Components</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/react-navigation"><li>React Navigation</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/react-icons"><li>React Icons</li></a>
  <a href="https://classic.yarnpkg.com/pt-BR/package/react-native-vector-icons"><li>React Native Vector Icons</li></a>
</ul>


# :hammer: How to use

## :green_book: Backend

<p> First things first, it is necessary to have the <a href="https://www.docker.com/">docker</a> installed. After, run: </p>

``docker run --name postgres -e POSTGRES_PASSWORD=fastfeet -p 5432:5432 -d postgres
``

``docker run --name fastredis -p 6379:6379 -d redis:apline
``
<br/>
<p>After this, run on backend directory: </p>

``yarn
``

``yarn sequelize db:migrate
``

``yarn sequelize db:seed:all
``

``yarn dev
``

``yarn queue
``

## :computer: Web

<br/>
<p>For web, is a little bit simpler. Just run on web directory: </p>

``yarn
``

``yarn start
``

## :iphone: Mobile

<br/>
<p>Configure the android/iOS environment (<a href="https://docs.rocketseat.dev/ambiente-react-native/introducao">Rocketseat Docs</a>). After, run on mobile directory: </p>

``yarn
``

``npx react-native run-android
``

``npx react-native start
``
<br/>

## :black_nib: Login

<p>Once the steps above are done, you will be ready to run FastFeet. For login in web app use:</p>
<p align="center">login: admin@fastfeet.com</p>
<p align="center">password: 123456</p>

<br/>

<p>For mobile login, just use the courier id.</p>

<p>Enjoy!</p>

## :memo: License

This project is under MIT license. Look [License](LICENSE.md) for more details!


