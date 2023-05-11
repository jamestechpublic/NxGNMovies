NxGN MOVIES (by James Lombard, May 2023)
========================================

Tech Stack
----------
Visual Studio 2022 (WebApi)
Visual Studio Code (Angular)
Dapper
SQL Server
Angular 15
Angular Material

Project Files
-------------
Readme.txt (this file)
MoviesUIsrc.zip (front-end only the src folder)
MoviesAPI.zip (back-end)
MoviesDB.bak (backup database file)
Movies.mp4 (demo clip of project)

Running the Project
-------------------
The Database Fille:
1. Please retore the MoviesDB.bak to your local SQL Server.
2. Ensure the connection string in appsettings.json file in the WebApi (back-end) point to your restored database

Back-end:
	Get project folder in MoviesAPI.zip
	Run the WebApi from Visual Studio 2022

Front-end: 
	Create MoviesUI angular project
	The src folder is in MoviesUIsrc.zip
	install additional packages
	Run from visual studio (for example)

NOTES & POSSIBLE IMPROVEMENTS
-----------------------------
- It was decided not to implement ag-grid in-line editing as this would nullify the add/edit component's edit purpose.
- The WebApi should use the ILogger in production to log error etc.
- To download the csv file, the front-end implements a temporary link:
   a. No need to add the file-saver module (adding to a bloated front-end project)
   b. Easier to implement
   c. Safer, as it uses the browser's download functionality.
- The CSV download should move the the services component.


Some Friendly Professional Notes
--------------------------------
- Upgrade to Blazor technology
- A similar full CRUD blazor project (including the WebAPI):
	107mb 1045 files
- This Angular project (only front-end):
    964mb 46578 files
- Blazor uses one language for front and back-end (C#)
- Blazor became the fourth official Web language in Oct 2020 (W3C)
- Browser Edge, Chrome and Firefox directly interpret Blazor, no more JavaScript
- Blazor uses .NET Core which is stable with better security
- Blazor was design as an enterprise development technology
- Angular is dependent on third-party modules
- Blazor only uses Microsoft technology
- Blazor front-end components are ready and reactive out of the box
- Blazor is smaller, faster and more professional to develop and maintain
- More and more companies are moving over to Blazor








