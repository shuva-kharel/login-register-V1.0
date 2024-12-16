# 1. install node modules
## `cd frontend`
## `npm install`
<br>
# 2. run frontend
## `npm run dev`
<br>
# 3. add .env file
## `touch .env`
## paste this:
```
MONGO_URI=<MONGO_API>
PORT=5000
JWT_SECRET=mysecretkey
NODE_ENV=development

MAILTRAP_TOKEN=<MAILTRAP_API>

CLIENT_URL= http://localhost:5173
```
<br>
# 4. run backend
## cd ..
## `npm run dev`
