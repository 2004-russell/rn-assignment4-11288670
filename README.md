# rn-assignment4-11288670

This is a simple React Native application for job seekers. The app consists of a login screen and a homepage where users can browse and add job listings. Below is a brief description of each component used in this application.

COMPONENTS
App.js
This is the main component that controls the navigation between the LoginScreen and HomepageScreen. It uses a state variable currentScreen to track the current screen being displayed and another state variable userData to store the user's name and email.

State Variables:
currentScreen: Tracks the current screen ('Login' or 'Home').
userData: Stores user information (name and email).

Functions:
handleNavigate(screen, data): Navigates between screens and updates user data if provided.
Usage:
The App component initializes the application and handles screen navigation.

LoginScreen.js
This component provides the user with a login interface. Users can enter their name and email to log in.

State Variables:

name: Stores the entered name.
email: Stores the entered email.
Functions:

handleLogin(): Triggers navigation to the homepage with the entered name and email.
Usage:
The LoginScreen component collects user credentials and navigates to the homepage.

HomepageScreen.js
This component displays job listings, including featured and popular jobs. Users can also add new jobs through a modal form.

State Variables:

featuredJobs: List of featured job objects.
popularJobs: List of popular job objects.
modalVisible: Controls the visibility of the modal for adding new jobs.
jobDetails: Stores the details of the job being added.
Functions:

handleAddJob(): Shows the modal for adding a new job.
handleSaveJob(): Adds a new job to the featured jobs list and closes the modal.
handleChange(name, value): Updates the job details being added.
Usage:
The HomepageScreen component displays job listings and provides functionality to add new jobs.

JobCard.js
This component represents a single job card in the featured jobs section.

Props:

job: Job object containing details like title, company, salary, location, and icon.
Usage:
The JobCard component is used to display individual job details in a card format.

PopularJobCard.js
This component represents a single job card in the popular jobs section.

Props:

job: Job object containing details like title, company, salary, location, and icon.
Usage:
The PopularJobCard component is used to display individual popular job details in a card format.

Usage
Login Screen:

Enter your name and email.
Click the "Log in" button to navigate to the homepage.
Homepage:

Browse through the featured and popular job listings.
Click the "Add Job" button to open the modal for adding a new job.
Fill in the job details and click "Save" to add the job to the featured jobs list.

SCREENSHOTS.
![image](https://github.com/2004-russell/rn-assignment4-11288670/assets/151689516/9a223558-e60e-4aa4-a602-b6a9e6379966)
