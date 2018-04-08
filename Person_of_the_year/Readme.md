# Person Of the Year #
This web application allows user unput to search thru a set list of person of the year. There are only currently one index page and one results page. This was built using .NET core framework, no scaffle was involved.

## Author:
Tiger Hsu <br>

## Attribution
Parts of this code is attributed to
Amanada Iverson <br>
Phil Werner <br>

## Version:
2.0.0 

## Overview
This is my first exposure to the .NET frame work using C#, This is an application that allows for
a user to search dates by using the Model View Controller model. Model is an object constructor which we had been given an CSV file and created an array with it. Controller which takes in a user form id / input and has the GET POST methods attached to them, decides where to directs to the view page. The View page only has two Razor pages one for input and one for results page.
During the start the user will be prompted to input a start year anything between 1964 -2016.
Then the next input is the end year anything greater than the input year but less than 2016.
Then the user will be redirected to a results page showing the database of information.

## Getting Started
1. Clone the repository to your local machine.
2. Select into application directory where the *AppName.sln* exist.
3. Open the application using *Open/Start AppName.sln*.
5. The website will run on your default web browser routing to the main home page.

## Example -Index Page

![alt text](/Person_of_the_year/Time_Person.JPG)
This is the Home landing page

## Example - Results Page
![alt text](/Person_of_the_year/Time_Example.JPG)
This displays The results of looking thru years 2000 - 2014

## Architecture
 - C# ASP.NET Core application.
 - MVC architectural design pattern.
 - Entity Framework - built in Visual Studio
 
## Credits
Aurther Allen <br>
Kevin Farrow <br>
Brent William <br>
Philip Werner <br>
Josh Taylor <br>
Amanda Iverson <br>

## Resources
StackoverFlow
Microsoft Docs

## License
MIT License

## Change Log

04-08-2018 4:59pm 
