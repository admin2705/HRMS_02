HRMS – Human Resource Management System.
A full-stack HRMS (Human Resource Management System) designed to automate and streamline HR operations such as employee management, attendance tracking, leave management, payroll processing, and role-based access control.

This application is built using Java (Spring Boot) for the backend, Angular for the frontend, and MySQL as the relational database, following industry-standard best practices

_____________________________________________________________________________________________________________________________________________________________________________
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

** HRMS Backend – Human Resource Management System**
hrms-02/
├── QuantumsoftHrms  
|       └──src/environments
│           ├── environment.ts
│           └── environment.prod.ts
│
└── backend
    └──src
        ├── main
        ├── resources
        └── application.properties

** HRMS Frontend – Build Guide **   
// Install Node.js & npm
node -v
npm -v
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs

//Install Angular CLI
npm install -g @angular/cli@17
ng version
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
ng build --configuration production --no-prerender

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
** HRMS Backend – Build Guide ** 
java -version
mvn -version
git clone https://github.com/admin2705/HRMS_02.git

sudo apt update
sudo apt install openjdk-17-jdk -y
java -version
sudo apt install maven -y
mvn -version

sudo update-alternatives --config java
mvn clean install
mvn clean install -Dmaven.test.skip=true
______________________________________________________________________________________________________________________________________________________________________________







