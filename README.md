# Description
A project based on author wishing to sell his/her books
# Project Structure 
Each Feature/ Requirements will have their own folder.
Each Folder will contain a :
- router -- the REST API endpoints
- service -- Interacting with Database client
- controller -- Business logic

# Prisma Guide 
There are three main features that prisma has
- prisma client -- functions that we are interacting with the database
- prisma migrate -- version control for our database
- prisma studio -- UI Database

# Prisma CLI

To initialise prisma :
```
yarn prisma init or npx prisma init
```

To generate our prisma client :
``` 
yarn prisma generate or npx prisma generate
```

To create new migrations whenever we change our models :
```
yarn prisma dev --name enter_description or npx prisma dev --name enter_description
```

To run our UI database dashboard :
```
yarn prisma studio or npx prisma studio
```

To create tables based on an existing migration :
```
yarn prisma migrate deploy
```

# Additional Resources  
https://www.prisma.io/