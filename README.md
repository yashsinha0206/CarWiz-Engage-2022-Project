# CarWiz-Engage-2022-Project
Submission repository for the Microsoft Engage'22 program

This repository consist of individual links of the fronted and backend repository of my website, please follow below:

Frontend: https://github.com/yashsinha0206/Engage-Carwiz-frontend

Backend: https://github.com/yashsinha0206/Enagage-Carviz-backend.git

Website: https://carwiz.netlify.app



### Points to Remember while running the files on your system:
 

1. Set up MongoDB Compass and Postman on your system.

2. After setting up MongoDB Compass on your local system, create a database, and upload the dataset (json file: present in the repository).
**Note: Data Cleaning has been performed before execution of the above instructions.**

3. Now, in the backend, in the "services" folder go to "db.connection.js" file, go on line -

- var inst1 = mongoose.createConnection(paste the link of your MongoDB database)

4. **Before running/executing the backend file in your ide, open terminal and write:**

   **Getting started**

      - Install dependencies: `npm install`
      - Start the project: `nodemon app`

5. **Before running/executing the fontend file in your ide, open terminal and write:**

   **Getting started**

      - Recommended `node js 14.x` and `npm 6+`
      - Install dependencies: `npm install` or `yarn install`
      - Start the project: `npm run start` or `yarn start`

6. During using the application, when searching for "Company Name" (under Company Details), do remember that the Company name is case sensetive as per the database used in the backend. So, write the Company Name same as given in the dataset.




## CarWiz Website

![image](https://user-images.githubusercontent.com/74976948/170839223-e57c4b7b-4c99-40cd-beff-f970c67d6061.png)

![image](https://user-images.githubusercontent.com/74976948/170839229-79dd336d-b018-4968-b1ac-17fd52dd58d6.png)

![image](https://user-images.githubusercontent.com/74976948/170839231-bc3f84a0-afbd-4c39-97ec-08b4fce80155.png)

![image](https://user-images.githubusercontent.com/74976948/170839233-e3d45d67-4652-4e44-8516-0bb8482b713d.png)

![image](https://user-images.githubusercontent.com/74976948/170839237-651e4cfa-8c8d-4bd0-9dac-2d5876a9315d.png)

![image](https://user-images.githubusercontent.com/74976948/170839250-ea6382cc-48aa-4240-9286-1a8c83306a0b.png)




## Project Idea and Working

Using data analytics to help customers as well as the industry to take informed decisions.



## Backend:-

https://github.com/yashsinha0206/Enagage-Carviz-backend.git

1. Node (NodeJS)

Node allows to write JavaScript code that runs directly in a computer process itself instead of in a browser. Node can, therefore, be used to write server-side applications with access to the operating system, file system, and everything else required to build fully-functional applications.

In my node file, in the controller node we have “cars.controller.js” where APIs are built. The Controller node supplies API.

The APIs developed were used to query data according to several specifications of cars which were later visualized in frontend


2. MongoDB Compass

I used the MongoDB Compass desktop application to go through the data stored in my MongoDB database. 

**The database was created on the basis of the dataset provided by the Data Analysis Engage challenge and after data cleaning.**


3. Postman

I used Postman for API building and testing.

Postman Documentation: https://documenter.getpostman.com/view/21119224/UyxqC3wT


**The APIs developed will be used to compare several specifications of cars and perform data visualization (demand of the problem statement).**

Few of the API examples: 

i. Get all cars data

ii. Companies vs no. of cars

iii. Avg price vs power


4. Heroku

After managing the database and successfully developing the APIs, I used Heroku to deploy the backend (integrating MongoDB Atlas).




## Frontend:-

https://github.com/yashsinha0206/Engage-Carwiz-frontend

1. React

“React.js” is an open-source JavaScript library that is used for building user interfaces specifically for single-page applications. It's used for handling the view layer for websites.

2. Material UI

Material-UI is simply a library that allows us to import and use different components to create a user interface in our React applications.

In this project I used a web template to save time and molded it as per my needs and requirement. (https://v4.mui.com/)

3. Netlify

Netlify is a platform for building and deploying/hosting websites.

After completing the frontend part on my system and integrating it with the backend, I hosted the website using Netlify. 

My website (CarWiz): https://carwiz.netlify.app






