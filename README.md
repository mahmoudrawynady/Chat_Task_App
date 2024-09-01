# chat_App

A new Flutter project for nagwa classes app for mobile, tablet,macos,linux,windows.

## Getting Started

**Project Setup**

1- Flutter Version used for this is v3.16.9.
2- To can run this project please download melos and setup it since this project use
**Mono Repo** Concept:
- [Melos Website to configure it](https://invertase.docs.page/melos/getting-started#installation)
-  [Important Note] (After installing and adding it to your project run (*/melos bootstrap*/) command to
establish the project) .


## Code Structure

**Project structure**

1- Project divided into packaged and main chat app, so if you want to run will run the **main.dart** file 
which is the host app.

2- Under the packages folder will find all the needed packaged for handling the code like:
  - [Network Kit package] >> To handle all network business
  - [Chat Kit package] >> To handle all logic related to the chat functions..
  - [Core Package] >> Contains all core widgets and classed.
  - [Core Business Package] >> Contains all core business logic.

3- Clean Architecture used a Project structure.

**Offline Technique**

- Used Hive, secure storage and internal file system custom arch developed by my own to handle all things
related to caching data using **path_manager** class.






