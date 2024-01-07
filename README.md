
# react-express-boilerplate

## Sequelize commands

// Generates a sample User model
npx sequelize model:generate --name User --attributes username:string,email:string,hashedPassword:string

// Migrate tables
npx dotenv sequelize db:migrate

// Generate seeder file
npx sequelize seed:generate --name demo-user

// Migrate seed files
npx dotenv sequelize db:seed:all

// Undo seeder migration
npx dotenv sequelize db:seed:undo:all

// Undo table migration
npx dotenv sequelize db:migrate:undo:all