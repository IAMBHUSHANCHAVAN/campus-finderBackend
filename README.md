# Campus-finder Backend

This repository contains the backend code for Campus Finder, a platform that helps students find and explore various schools, colleges, and investors. 
**The backend is developed using Node.js, Express.js, and MongoDB, and it leverages several npm packages to ensure seamless functionality. The backend's key features include user authentication, review management, profile editing, and powerful CRUD APIs for managing colleges and schools. also there the user can add their favorite colleges and schools to a personalized wishlist. For security purposes, certain functionalities are restricted to the admin, granting them exclusive privileges to delete or add colleges and schools, as well as edit existing entries.**

## Getting Started

To use this backend, follow the steps below:
1. Clone the project repository using the following command:`git clone <repository_url>`
2. Install the required packages:`npm i`
3. Create a .env file in the root directory of the project. Inside the .env file, add the following **env variables**:`PORT=`,<br>`CONNECTION_STRING=YOUR_DATABASE_CONNECTION_STRING`, <br>`JWT_SECRET=`, <br>`JWT_EXPIRE=`, <br>`COOKIE_EXPIRE=`
4. After setting up the .env file and installing the dependencies, you can start the server by running:
**`npm start`**.

The API should now be up and running, ready to serve incoming requests.

## Api Features:

* **User Authentication**: Implementing a secure user authentication system to enable users to create accounts, log in, and access personalized features.

* **Profile Editing**: Allowing users to modify their profile information, making it easier to keep their details up to date.

* **Personalized Wishlist**: Enabling users to create a personalized wishlist by adding their favorite colleges and schools, allowing for easy access and organization of preferred choices.

* **Search Feature**: Allowing users to search through different colleges and schools.

* **Review Management**: Facilitating users to post, view, and manage reviews for different schools and colleges, contributing to an informed decision-making process.

* **Powerful CRUD APIs**: Providing Create, Read, Update, and Delete APIs to manage colleges and schools, ensuring efficient data management.

* **Admin Privileges**: Limiting certain functionalities, such as adding, deleting, or editing entries, to the admin role to maintain data integrity.

## To check api
If you are using the Thunder client to test the API, you can import the **api_collection.json** file provided in this repository. The collection contains sample API requests that you can use to interact with the backend.


For any issues or inquiries, please don't hesitate to contact.

Happy coding! 🚀






## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.
