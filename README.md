# Angular example project
About: Social media para gatinhos

Using typescript
Components, services, routers, interecptors

How to build

# on API folder:
--INSTALL ANGULAR
npm install -g @angular/cli

--CHECK INSTALLATION
ng version

--EXECUTE SERVER
npm start



# on gatitoobook folder:
--SETUP ANGULAR
npm install -g @angular/cli
ng version
npm install --save-dev @angular-devkit/build-angular

--INSTALL PACOTES DE EXTENSAO
npm install --save-dev prettier #formatador de codigo 
npm install --save-dev tslint-config-prettier
npm install --save-dev tslint-plugin-prettier

--EXECUTE APP (DEV)
ng serve
ng s -o

--INSTALL PACKAGE TO RUN ON APPLICATION SERVERS
npm i -g http-server

--CREATE BUILD (TO APPLICATION SERVERS)
ng build --prod

--EXECUTE APPLICATION AFTER BUILD
cd dist\
ls
cd [projectname]
http-server

