# Demo Flask
## se creó el entorno virtual 
1. pyenv virtualenv 3.10.4 msjelectronica
2. pyenv local proyecto
3. pip install flask
4. pip install -r requirements.txt (Para esto se cambió en el requirements.txt el MarkupSafe==2.0.1 a       MarkupSafe==2.1.1 y se borró la linea siguiente de pkg-resourses==0.0.0)
5. flask init-db
6. flask run
## Dependencies
To install the required dependencies, please follow these steps:

1. Open a console.
2. Go to the project directory (with `cd` command).
3. Write and execute `pip3 install -r requirements.txt`.

## Initializate DB
To run the app, you need to provide a Microsoft account for the app to send/receive emails. To add this account follow these steps:

1. Open the file `schema.sql`.
2. Locate the line `INSERT INTO credentials (name,user,password) VALUES ('EMAIL_APP','developmentcapstone', '$TR41NC0URS3R4$')`.
3. Replace `developmentcapstone` with the email address.
4. Replace `$TR41NC0URS3R4$` with a password to access the email account.
5. Run flask init-db`` on the project directory.

## Run application
For run the app you need to use `flask run` on the project directory.
