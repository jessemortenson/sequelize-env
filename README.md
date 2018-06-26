# sequelize with a .env example

*important*: usually you would *not* commit a `.env` file to the repository. This repository HAS a 
`.env` file for demonstration purposes.

This shows how to modify sequelize configuration in `index.js` and slightly modify `config.json` to 
`config.js` so that it works with the dotenv package (and a `.env` file).

The REASON to use an environment file is to allow each team member to have their own local 
development credentials stored on a private `.env` file, instead of in the shared `config/config.js` 
sequelize config. This way each member can push/pull to/from the repo without encountering MySQL 
connection errors.
