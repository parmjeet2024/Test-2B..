JavaFX Login and CRUD Application
Overview
This JavaFX application consists of two scenes:

Login Page
A basic login form where users must enter a valid username and password.

CRUD Page
Once authenticated, users are redirected to a second scene where they can:

Create (Add)

Read (View)

Update

Delete
entries in a simple table displaying name and email information.

Features
Two JavaFX scenes (Login and CRUD)

TableView for displaying dynamic data

Form validation for login and data inputs

Alerts for invalid actions

Preloaded sample data

Scene switching after successful login

Login Credentials
To access the CRUD operations, use the following credentials:

Username: Parmjeet

Password: Bhathal

Any other credentials will result in an error message.

File Structure
graphql
Copy
Edit
src/
├── Main.java         # Launches the application and handles login logic
├── CrudScene.java    # Contains CRUD interface and logic
├── Person.java       # Data model for person (name, email)
How to Run
Install JavaFX SDK
Download JavaFX from https://openjfx.io and unzip it.

Compile and Run in IDE (e.g., IntelliJ or Eclipse)

Add the JavaFX lib/ directory to your project libraries.

Set VM options to include:

css
Copy
Edit
--module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml
Replace /path/to/javafx-sdk/lib with your actual path.

Run the Main.java file
This will open the login screen. After logging in successfully, the CRUD interface will appear.

