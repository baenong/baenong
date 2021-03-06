<!---
baenong/baenong is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

NomadCoder Profile : [baenong](https://nomadcoders.co/users/anminsnusa)   
Study Site
[Dunkenbee PVP](https://wongbaenong.github.io/DrunkenbeePVP)
[Utube](https://https://utube-study.herokuapp.com)

Complete
-
> HTML
* KokoaTalk
```html
<body>
  <span>Hello World!</span>
</body>
```

> CSS
* KokoaTalk
```css
.hello {
  display: flex;
  flex-flow: column nowrap;
}
```

> Javascript
- Todo list
- Paint
```javascript
const span = document.querySelector(".greeting");
span.classList.add = "Hello";
span.innerText = "World";
```
   
> YouTube Clone Coding
- Node.js
```javascript
console.log("Hello World!");
```
- Express.js
```javascript
import "dotenv/config";
import express from "express";
import session from "express-session";
import MongoStore from "connect-mongo";

const app = express();
app.set("view engine", "pug");
app.set("views", process.cwd() + "/src/views");

app.use(express.urlencoded({ extended: true }));

app.use(
  session({
    secret: process.env.COOKIE_SECRET,
    resave: false,
    saveUninitialized: false,
    store: MongoStore.create({ mongoUrl: process.env.DB_URL }),
  })
);

const PORT = 4321;
app.listen(PORT, () => {console.log(`Server Listening on ${PORT}`)});

```
- Pug
```pug
extends base.pug
block content
  h1 Hello World!
```
- MongoDB
```
show dbs
```
- mongoose

In Progress
-

Goal
-
> CSS Layout
   
> Typescript

> GraphQL

> ReactJS

> React Native

> Instargram Clone Coding
