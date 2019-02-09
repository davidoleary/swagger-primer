# Skeleton project for Swagger

- This is just the result of this nice swagger tutorial https://scotch.io/tutorials/speed-up-your-restful-api-development-in-node-js-with-swagger
- To add swagger to an existing project follow: https://blog.cloudboost.io/adding-swagger-to-existing-node-js-project-92a6624b855b

Install swagger and create project

``` javascript
// only for starting a new project
sudo npm install swagger -g
swagger project create swagger-example
```

Run one of
``` javascript
swagger project start
swagger project  start -m // mock mode
```

Then run the swagger editor for testing api via UI:
``` javascript
swagger project edit
```

Run as normal project
```
npm start
```
