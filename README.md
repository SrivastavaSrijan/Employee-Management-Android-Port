# employee-management-android
This application to generate values for employees from a database seamlessly and randomly, add said employee's details to a database (SQLite for Android) and display said employees in a table with the option to search, sort or edit details. Its an Android port of my JavaFX application. You can find the Desktop application here - https://github.com/SrivastavaSrijan/employee-management-app-desktop
This Android app was developed using Material Design and Android Jetpack by implementing the latest design guidelines such as RecylerView, SearchView and CardView.
For streamlining design, I used Circular Progress Buttons to intimate statuses to the user and define a  Call to Action.
It uses JavaFaker internally and stores the data using Android Room built on top of SQLite.
I used a simple CustomFilter for searching for employees. The contents were populated using RecylerView. Android CardView was used for the dashboard design on the home page.
It was then simulated and debugged on GenyMotion.
