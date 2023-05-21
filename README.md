
# Pembayaran SPP (School Tution) - Back-end

Another final project in my second year. This is the backend part. If you want to find the frontend part, just type 'frontend-pembayaran-spp' in my repository.
## Environment Variables

This project didn't implement environment variables, cuz all the SECRET KEY already hardcoded in each file (usually at the top of the file). 

There is only a database config that available in the file config/config.js. 


## Deployment
Package manager already updated using pnpm. Install the dependencies using the command.

```bash
  pnpm install
```

Then initiate your database in your local server. Name of the DB should match with the database name in file config.js. Now, you can run migration or simply import the sql file that I have been provide in this repository. 

If you want to experienced running migration, you can use command
```bash
  pnpm sequelize db:migrate
```

Now you can run this with command

```bash
  pnpm start
```

PS: Watch out! There is nodemon in this programme