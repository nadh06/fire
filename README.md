NAME : SYAFIQAH NADHIRAH BINTI SHAWAL
STUDENT ID : 2023435818
GROUP : T5CDCS2703B1
LECTURER : SIR MUHAMMAD ATHIF BIN RAMLAN


PROJECT BACKGROUND : 

AngularFire is the official library that bridges Angular applications and Firebase services, allowing developers to easily integrate Firebase into their Angular projects. It is maintained by the Angular community and Firebase team and provides seamless access to Firebase's backend services with tools and APIs optimized for Angular development.

1. Build a web application using Angular framework and Firebase suite of bakend services.
2. Implement real time data synchronization using Cloud Firestore for structured data storage and Cloud Storage for managing and delivering user generated content like images and files in Firebase.
3. Authenticate your users using Firebase Authentication supporting methods such as email or password, Google and other providers.
4. Publish the web application by deploy the web app on Firebase App Hosting.


DISCUSSION :

The objective of this lab was to integrate AngularFire with a web application in order to apply real-time database functionality. Other than that, in this lab, I learn how to use AngularFire in order to create web applications by implementing and deploying a chat client using Firebase products and services but there are various challenges which I face while doing this project.

One of the challenges was the configuration of the versions of Firebase to avoid compatibility issues, since Firebase is designed to work with specific versions, such as Angular. Using an older version of AngularFire with a newer version of Firebase might cause some methods or features not to work, leading to error which requires careful attention to documentation and dependency alignment.

Moreover, when I want to send messages such as "Hello" and these messages are supposed to be in the Firebase Console. Despite executing the code,those messages did not appear at all and it was caused by improper Firestore configuration and incorrect database.  It is crucial that the Firestore is properly set up in the Angular environment, and the database rules allow authenticated read/write access. 

Next, authentication plays a vital role in chat applications, in a friendly chat, the user authentication identifier is not shown. This issue may stem from misconfigurations in the authentication flow or missing user data fields during authentication.Other than that, a friendly chat web can't open and error occurs when replacing a local host link with a domain that has been added in an authorized domain. This suggests issues with Firebase hosting settings or incorrect domain registration in the Firebase Console, which can prevent the app from functioning correctly on production URLs.

Apart from this, when attempting to send any image in the chat, the place holder for the  image keeps loading indefinitely and the image itself never appears in the web-friendly chat window. This behaviour also extended to messages, especially when opening a new chat session. These issues are typically related to problems in the Firebase Storage configuration, such as incorrect file paths, inadequate upload error handling, or storage rules that prevent proper access. 

It was a really good learning experience, and despite all that, it enhanced my understanding of the services Firebase provides and the importance of managing version, database configuration, authentication setup and image upload workflows. This is because web development is going to take off into troubleshooting skills, too and by addressing these challenges, developers can create robust and user-friendly chat applications.


<<<<<<< HEAD
# Friendlychat

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
=======
# fire
>>>>>>> 189a9a6b6f8e2d7c3ca1b65c4046cb8e25605bdb
