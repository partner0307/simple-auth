# simple-auth - Epic dragons

This project is small web called "Epic dragons". The only purpose of this project is to create simple authentication
secured by `httpOnly` cookies for SPA with separated backend and frontend.

<a href="https://app.daily.dev/ItamiWorld"><img src="https://api.daily.dev/devcards/dab7f860f7394fc0803744e36b99fc39.png?r=n4c" width="200" align='right' alt="Tadao Minami's Dev Card"/></a>

Project is implemented in MEVN stack:

- MongoDB
- Express.js
- Vue.js
- Node.js

For authentication are used JSON Web Tokens (JWT). Those are saved in httpOnly cookies. In frontend are httpOnly cookies
unreachable so for protecting routes and other stuff in frontend is used state of Vue application. Easy state management is
done by `Vuex`.

## commands

- `npm run backend` - starts the express server
- `npm run frontend` - starts vue development server
- `npm run dev` - starts both => backend and frontend
- `npm run build` - installs dependencies and builds the frontend
