<h1 align="center"> YouTube API app </h1>

## Step-by-step

You need to create a new project in Google Cloud, create the credentials for OAuth2.0, or (keep working)

The project allows the user login with Google OAuth2, and retrieves the user's Access Token. 

<a href="https://ibb.co/MpFh6qx"><img src="https://i.ibb.co/HY52dmf/asd.jpg" alt="asd" border="0"></a>

The access token is used for making authorized requests on behalf of the user's account.
An .env file must be created with the parameters:
<br>
```
PORT=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_REDIRECT_URL=
```

## Prerequisites
Tools that we need to run this app:

- ***[Node.js](https://nodejs.org/en/)***
- ***[Node Package Manager](https://www.npmjs.com/get-npm)***

<br>

## :computer: Instalation
```
npm run start:dev
```
<br>

## :warning: devDependencies

@types/express<br>
@types/passport<br>
dotenv<br>
nodemon<br>
@types/passport-google-oauth20<br>
ts-node<br>
typescript<br>
