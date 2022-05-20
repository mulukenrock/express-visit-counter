# express-portfolio-visit-counter-api

## Sample `.env` file

```
HASURA_GRAPHQL_URL=http://localhost:4040/v1/graphql
HASURA_GRAPHQL_ADMIN_SECRET=secret
PORT=4041
CORS_ALLOWED_SITES=["http://localhost:8081"]
```
## Build Setup
```
# start express
$ yarn dev
```
## Deploy to heroku
``` 
$ yarn heroku:login
$ yarn heroku:create app_name
$ yarn heroku:deploy
$ yarn heroku:logs app_name
```