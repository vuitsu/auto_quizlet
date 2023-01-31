# auto_quizlet
A script that opens quizlet.com each time the computer is started.

## Informations

Before starting the project, you need to change the URL of the website you want to visit each time you start your computer in the python code.
Your [python file should look like this](https://user-images.githubusercontent.com/96443442/215823096-26eb7b56-dc43-44b1-a54d-089e9d8e9593.png).

## Important

To run this code automatically when your computer starts up, you can place it in a .py file and set it as a scheduled task in your operating system's task manager. The steps vary depending on your operating system, but here is an example for Windows :

    - Create a .py file with the above code and save it to your computer.
    - Press Windows + R to open the Run command.
    - Type "taskschd.msc" and press Enter to open the Task Manager.
    - Click on "Create a basic task" in the Action menu.
    - Fill in the details of the task, such as name and description, and click "Next".
    - In the Triggers section, click "New" and set the trigger to "On startup".
    - In the Actions section, click on "New" and set the action to "Start a program".
    - Select the .py file you have created and click "Next".
    - Click "Finish" to save the task.

Now, every time you start your computer, the website will automatically open in your default browser.
