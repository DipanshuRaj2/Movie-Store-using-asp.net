# MovieStore
# Movie-Store-using-asp.net

Project Title: Movie Store MVC(Model View Controller) project in dot net

This report outlines the implementation of a movie store application leveraging ASP.NET 
MVC for backend development and the power of abstraction through HTML, CSS, and 
JavaScript for the user interface.


Abstraction for a Clean Separation

The key to a well-structured ASP.NET MVC application lies in abstraction. This concept 
separates the application's concerns into distinct layers:

• Model: Represents the data layer, encapsulating data entities (like Movie) and their 
properties. The model layer might also contain business logic related to data 
manipulation.

• View: Embraces the presentation layer, utilizing HTML, CSS, and potentially JavaScript 
to display information retrieved from the model. Views are typically Razor (.cshtml) 
files that focus on how data is presented to the user.

• Controller: Acts as the intermediary layer, handling user requests. Controllers interact 
with the model to retrieve or manipulate data and select the appropriate view to 
display the results.

This separation offers several benefits:

• Maintainability: Changes to one layer (e.g., updating the user interface with new CSS 
styles) don't necessarily impact the others. This improves code maintainability and 
reduces the risk of unintended side effects.

• Testability: Each layer can be tested independently, making it easier to identify and fix 
bugs early in the development process.


• Scalability: The application can be easily extended with new features by adding new 
views, controllers, and model components without affecting existing functionalities.

Introduction

This report outlines the implementation of a movie store application using ASP.NET

MVC framework. ASP.NET MVC is a popular design pattern for building web

applications that separates concerns between Model, View, and Controller
components. This report will detail the functionalities, structure, and potential benefits
of this approach.

Functionalities

The movie store application can provide various functionalities depending on its 
complexity. 

Here are some core features:
. Search the Movie name.

. It has an admin section that includes movie details, table, add a movie name.

. In particular movie section it include movie name, which type of movie (action,

adventure, comedy, romance, relationship), actor name and director.

. This website has Four button that is Home, About, Admin and Login.
