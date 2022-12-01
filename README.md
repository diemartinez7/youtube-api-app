<h1> YouTube API app </h1>

<br>

## :rocket: Goals

The project allows the user login with Google OAuth2, and retrieves the user's Access Token. 

<a href="https://ibb.co/MpFh6qx"><img src="https://i.ibb.co/HY52dmf/asd.jpg" alt="asd" border="0"></a>

The access token is used for making authorized requests on behalf of the user's account.

<br>

## :footprints: Step-by-step

<ul style="list-style-type:disc">
  <li>You need to create a new project in Google Cloud,</li>
  <li>enable the YouTube Data API, </li>
  <li>complete the OAuth consent screen, </li>
  <li>create the credentials for OAuth2.0. </li>
</ul>

<br>

An .env file must be created with the parameters:

<br>

```
PORT=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_REDIRECT_URL=
```

<br>

## :computer: Instalation


```
npm run start:dev
```
<br>


## :gear:	Prerequisites
Tools that we need to run this app:

- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***

<br>


## :warning: devDependencies

@types/express<br>
@types/passport<br>
dotenv<br>
nodemon<br>
@types/passport-google-oauth20<br>
ts-node<br>
typescript<br>
