# Tutorial: Create a web API with ASP.NET Core

This tutorial teaches the basics of building a web API with ASP.NET Core.

In this tutorial, you learn how to:

- [x] Create a web API project.
- [x] Add a model class and a database context.
- [x] Scaffold a controller with CRUD methods.
- [x] Configure routing, URL paths, and return values.
- [x] Call the web API with Postman.
At the end, you have a web API that can manage "to-do" items stored in a database.

Overview
This tutorial creates the following API:

| API	                        | Description	            | Request body  | Response body
| :-------------------------- | :---------------------- | :------------ | :------------------- 
| GET /api/todoitems	        | Get all to-do items	    | None	        | Array of to-do items
| GET /api/todoitems/{id}	    | Get an item by ID	      | None	        | To-do item
| POST /api/todoitems	        | Add a new item	        | To-do item	  | To-do item
| PUT /api/todoitems/{id}	    | Update an existing item | To-do item	  | None
| DELETE /api/todoitems/{id}  | Delete an item    	    | None	        | None

The following diagram shows the design of the app.

![This is an image](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api/_static/architecture.png?view=aspnetcore-6.0)
