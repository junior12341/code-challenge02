## Superheroes API
The Superheroes API is a web-based application that enables you to track superheroes and their superpowers. It is built using Ruby on Rails and supports JSON responses.

## Table of Contents
Requirements
Setup
Models
Validations
Routes
Getting Started
Author
License
Requirements
To use this API, you need a computer that runs on either Windows 7+, Linux, or Mac OS, and Node.js 9.0+.

## Setup
To run the application, you can either access it through the provided link or run it on your local machine.

## Run with Link
To access the application through the provided link, open this URL: https://superheroes-api-zv0r.onrender.com/heros, and add either powers or heroes to the end of the URL to access the respective data. For example: https://superheroes-api-zv0r.onrender.com/heros/powers.

## Run on Local
To run the application on your local machine, follow these steps:

Clone the repository and open the code.
Run bundle install in the terminal to install all the necessary gems specified in the Gemfile.lock file of a Ruby project.
Run database migrations by running the command rails db:migrate.
Seed the database by running the command rails db:seed.
Start the server by running the command rails s.
Open the browser and go to http://127.0.0.1:3000.
Add either heroes or powers to the end of the URL to access the respective data. For example: http://127.0.0.1:3000/heroes.
## Models
The application has two models: Hero and Power. The Hero model represents the superhero, while the Power model represents the superpower.

## Validations
The application validates that the Hero has a name, a real name, and an alias. The Power model also validates that the superpower has a name and a description.

## Routes
The application has routes for the Hero and Power models. The Hero routes are /heroes and /heroes/:id. The Power routes are /powers and /powers/:id.

## Getting Started
To get started with the application, follow the setup instructions above.

## Author
This application was created by Hubert Jr.

## License
This application is licensed under the Apache 2.0 License.
