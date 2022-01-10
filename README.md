# Nemetos-Project-4

The website is a simple example website for a common company. The website has 5 + 2 pages and an admin page where you can log in and execute CRUD operation on the employees of the example company.

In this project you will find 2 Application. We name them "Back End" and "Front End" (but the projects are both backend).

The Front End project is a Web MVC Core project that has the classic Controller, Model and View system for a website.

The Back End project is also a Web MVC Core project, but the project is connected to a database with employees using Entity Framework and had API Controllers.

We separated the Content of the site from the Database. When a URL request is made, we get the content from the "Front End" project and the Database information from the "Back End" project.
