# User-Portal-backend

Project Title: User Register/Login Web Services
description: A user can register and login to the portal.
Prerequisites: Need to install the following softwares for this assessment
1. NodesJs - https://nodejs.org/en/download/(server side coding)
2. PostgreSQL - https://www.postgresql.org/download/(Database)
3. Sequelize ORM - npm install sequelize(MiddleWare to connect server with database)
3. IDE: Eclipse or VScode
4. Postman - Rest Client API

Setup
1. Import code from 'https://github.com/padmajak05/User-Portal-backend'
2. Install node modules using 'npm install'
	'package.json' have dependent node modules
3. start the app using 'npm run build'. Then cd dist and then node app/app.js
4. Open database and create the following 
	create database 'User',
	create schema 'db',
	Create login table with columns('id', 'username', 'password', 'creat_ts, 'lst_updt_ts')
	Note: Services have the related tables and columns
