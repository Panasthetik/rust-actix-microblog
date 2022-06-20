# rust-actix-microblog
A simple microblog starter template in Rust with Actix, Diesel and PostgreSQL. Need to add users / authentication and a React frontend. In progress.

## Instructions

PostgresQL needs to be installed

You need to initialize a new database "profiles_db" in the root directory of this project as follows:

``initdb /YOUR_PROJECT_PATH/rust-crud-postgres-app/profiles_db``

You then should perform the following:

``cargo build``   
``diesel setup``   
``diesel migration generate tweets_db``   
``pg_ctl -D /YOUR_PROJECT_PATH/rust-crud-postgres-app/tweets_db -l logfile start``        
``diesel migration run``    
``cargo run``


###
other instructions soon...