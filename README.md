# mysql

This RESTful Actix Web API examples illustrates how to connect to MySQL database using Mysql client library implemented in rust i.e  MySql database driver

Currently this RESTful API supports: 
- Add Bank
- Add Branch
- Add Teller
- Add Customer
- Get Bank
- Get Branch
- Get Teller
- Get Customer

The RESTful Actix Web API has below listed dependencies:
- [Actix Web](https://github.com/actix/actix-web) web framework for Rust
- [Serde](https://github.com/serde-rs/serde) for serializing and deserializing Rust data structures
- [MySQL](https://github.com/mysql/mysql-server) MySQL database server
- [mysql](https://github.com/blackbeam/rust-mysql-simple) MySql database driver

## Running The RESTful Actix Web API

First, open the terminal and clone the project using `git` (or you can simply download the project) and then change the directory:

```Rust
git clone https://github.com/lastemp/mysql.git
cd mysql
```

```MySQL
Open folder "mysql\sql" that contains the SQL files to create the tables in your local MySQL database server.
Please ensure you execute the SQL statements found in the files in your MySQL database server.
```

```Config file
Open file "xxx" located in path "mysql\xxx" and then 
change the configurations to match the credentials of your MySQL database server.
```

Once you are inside the project directory, run the application:

```Rust
cargo run
```