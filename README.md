# MVC (Model, View, Controller) - A Lecture By Jordan Ardoin

## Introduction

MVC is an architecture/design pattern used to develop software, emphasizing separation between the logic of the application and its display. Created in the 1970s by Trygve Reenskaug, MVC was intended used for desktop GUIs, but it has been widely adopted for design web applications

## MVC

M - Model - refers to the ‘shape’ of our data and how it is stored
V - View - refers to what is shown to the end-user
C - Controller - refers to the logic that handles requests, often interacting with both the Model and View

### The M - Model

How data is organized and stored will inform the functions of an application. Therefore, the Model is the foundation of the application as it will be responsible for defining the structure of all data. How a user is defined and how the user can interact with the application are some examples are the model; can they create an account, a profile, a post, etc.

### The V - View

The View is used to provide visual representation of the data coming from the Model. It acts as the channel between the user and the Model; As the user interacts with the application, the view changes in response. If a user, clicks a link to another page, the view will be altered. If a user submits a form, a message can be displayed for either success or failure to submit.

### The C - Controller

The job of the Controller is to handle user requests and to make updates to the Model, View, or both in some cases; It acts as the gateway between the user and the rest of the application. For instance, when a user creates an account, the controller will update the Model with that new account, and when that user logs in, the controller will serve a new View will be changed to reflect there logged in status.

### Why MVC?

- Separation of how data is stored, how it is displayed, and how user requests interact with the Model allows for:
- Organization of large web application
- Support of asynchronous
- Ease of modification
- Security - users cannot interact with the Model directly, only through the controller
