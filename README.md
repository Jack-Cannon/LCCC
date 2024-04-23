# Overview
The LCCC (Liquid Chromatography at the Critical Condition, or LC3x for short) web project was developed by the Chemistry department at the University of Memphis. This project involves a cloud hosted database of research experiments from the use of LCCC techniques to analyze complex mixtures and provide detailed information about their components. This doucment provides instructions on how to install and use the necessary software to run the web application on your local machine or hosting on a web server.

# Getting Started

## Prerequisites
1. Node.js.: Download [here](https://nodejs.org/en/download) (LTS recommended) - Comes with NPM (Node Package Manager) during instllation process.
   * Type `node -v` (check if Node is installed).
   * Type `npm -v` (check if Node Package Manager is installed).
3. npm: Type ```npm install -g @angular/cli@15.1.6``` OR ```npm install -g @angular/cli``` inside the terminal to install Angular globally (-g), specicially version 15.1.6.
4. Firebase JavaScript SDK & AngularFire library: Type ```npm install firebase @angular/fire``` inside the terminal to install the necessary packages and library for Angular/Firebase.
5. Clone Repository: Clone the source code by either directly downloading the files, or via Git CLI ```git clone git@github.com:Team-Chem/LCCC.git```.
6. Firebase: Requirements firestore folder in this path `node_modules/@angular/fire/compat/firestore` with this folder [here](https://github.com/Team-Chem/LCCC/tree/main/Firestore%20Dependencies%20Download).
7. * Download the firestore.zip file and this will contain the configured dependencies for the application. You will need to replace the files in the `firestore` folder with these.
8. Change directory: Open your termianl and CD into this directroy `LCCC-main`.
9. * Once within this directory, run this command to install necessary packages `npm install`.
11. Start Server: In your terminal, type ```ng serve``` which will start the application, then you can visit the application in the browser at this URL `http://localhost:4200/`.

# Troubleshooting
This sections covers known and potential issues when setting up your environment.

### Versioning
Check that your version of the software you installed are capatible with the version the application uses. 
* Node.js. incapabile version: Generally, the version of node.js. does not matter, however, if it does in the future, the working version as of 2023/10/31, is v19.8.1. Be aware, that odd numbers of node.js are not official supported by Angular.
* Deplying to hosting service: Since this application was origionally expected to be hosted on GoDaddy.com. You can try following this guide provided by medium.com [here](https://medium.com/@uk1992.me/web-application-deployment-angular-flask-godaddy-f43286f3c8fa)
* Firebase: Any issues revolving around firebase, such as, if you read issues with firebase in the command line or when you try to boot the angular server, be sure to replace your firebase folder in your directory, as the one stated in the prerequisites is necessary for the 
