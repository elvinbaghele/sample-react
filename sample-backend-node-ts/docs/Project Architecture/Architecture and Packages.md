# Architecture and Setup
rename or copy the `.env.SAMPLE` to `.env`<br/>
to start use `npm run start:dev`, this will start the server and you can go to `locahost:4000` to see the app. or change the port with `.env`

# Packages
this are external packages which are used in this project.
### typescript
we are using typescript for the project, this is the main language used in this project. 
### graphql
we are using apollo3 for the project, please check the documentation 
https://www.apollographql.com/docs/apollo-server/
### typeORM
`ormconfig.ts` will have all the configurations for typeORM, please check the documentation for more details.<br/>
actual implementation is in `/src/database/entity`<br/>
we are using entity in controller to set, get data from database.<br/>
connection object is propagated to all the controllers through apollo context.
### winston
winston is our main logger API, please check the documentation for more details.
