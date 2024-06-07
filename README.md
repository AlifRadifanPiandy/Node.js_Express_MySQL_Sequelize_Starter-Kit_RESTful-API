# Node.js Express MySQL Sequelize Starter Kit RESTful API

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)

This is a simple starter kit for building RESTful API in Node.js using Express. Intended for use with MySQL using Sequelize ORM.

## Getting Started

Clone the repository

```bash
git clone https://github.com/AlifRadifanPiandy/Node.js_Express_MySQL_Sequelize_Starter-Kit_RESTful-API.git
```

Enter into the directory

```bash
cd Node.js_Express_MySQL_Sequelize_Starter-Kit_RESTful-API
```

Install the dependencies

```bash
npm install
```

Set the environment variables

```bash
cp .env.example .env
```

Running the starter kit:

```bash
npm run dev
```

## Configuration

Variables for the environment

| Option             | Description                         |
| ------------------ | ----------------------------------- |
| SERVER_PORT        | Port the server will run on         |
| NODE_ENV           | development or production           |
| SERVER_JWT         | true or false                       |
| SERVER_JWT_SECRET  | JWT secret                          |
| SERVER_JWT_TIMEOUT | JWT duration time                   |
| DB_DIALECT         | "mysql", "postgresql", among others |
| DB_HOST            | Database host                       |
| DB_USER            | Database username                   |
| DB_PASS            | Database password                   |
| DB_NAME            | Database name                       |
| AWS_KEYID          | Access key ID                       |
| AWS_SECRETKEY      | User secret key                     |
| AWS_BUCKET         | Bucket name                         |

## Commands for sequelize

```bash
# Creates the database
npx sequelize db:create

# Drops the database
npx sequelize db:drop

# Load migrations
npx sequelize db:migrate

# Undo migrations
npx sequelize db:migrate:undo:all

# Load seeders
npx sequelize db:seed:all
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

Licensed under the [MIT License](LICENSE).
