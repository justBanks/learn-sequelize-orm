# learn-sequelize-orm
Install the Sequelize CLI (command line interface) globally:
`npm i -g sequelize-cli`

Create a new Node project: `npm init -y`

`npm i -S sequelize mysql`

Start by running `sequelize init` in your project’s root directory.

## Generating Models
`sequelize model:create --freeze-table-names --name User --attributes "email:string`

`sequelize model:create --freeze-table-names --name Context --attributes "name:string"`

`sequelize model:create --freeze-table-names --name Task --attributes "name:string, done:boolean, description:text"`
