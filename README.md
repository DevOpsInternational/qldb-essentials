### QLDB-Essentials

### WTF is QLDB

>QLDB is a No-SQL(Semi-SQL & Semi-NoSQL) Append-only database that provides an immutable, transparent, and cryptographically verifiable transaction log ‎owned by a central authority. Since it is a No-SQL database, It has the ability to store a lot of semi-unstructured data using a document-oriented data model. Moreover, it Uses SQL like data structure(Tables and Rows) and a language(PartiQL). So, it can leverage current SQL developers to offer robust ways to query and manage data

#### QLDB'S PartiQL Interface:
>Basic SQL Like Queries are included in ```resources/syntax.md``` file

#### Setup
>update ```.env``` file according to your QLDB Configuration
##### REST Server Setup
```
npm i
npm run start-rest
```
###### CURL Sample Commands:
>Sample CURL Commands for CRUD are included in ```resources/rest-queries.md``` file

##### GraphQL Server Setup
```
npm i
npm run start-graphql
```
###### Queries and Mutation Commands(Experimentation Only):
>Sample queries and mutations are included in ```resources/graphql-queries.md``` file


###### Special Thanks to :wave: [Lepozepo](https://github.com/Lepozepo) for making simple QLDB module used in this project


