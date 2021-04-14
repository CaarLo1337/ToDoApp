# ToDoList
My first AngularProject following a tutorial from [Johannes Schiel](https://github.com/Johannes-Schiel).
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.8.


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Json-Server

open new bash.  
make dir `mkdir server`  
change dir `cd server`  
Run `echo { \"todos\": [] } > db.json` to create db.json.  
Run `npm install -g json-server` to install [json-server](https://github.com/typicode/json-server).  
Run `json-server --watch db.json` to start json-server.  
