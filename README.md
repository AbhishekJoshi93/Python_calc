# Python_calc

PyQt5
It is a library that use GUI with python. It written in C++.

MVC
Model-View-Controller

Model->
In model section the database logic is stored. Also it contains the functions to insert, update, and other database queries are applied here. It helps the application for managing the data.

View->
In the view section the information is display to the user. It display all the data fetch from the model. Most important thing is that view doesnot communicate with the model.

Controller->
The controller works as the bridge between the model and view. The task of controller is that to respond to the user input and perform the interaction with model data and then display with the view.

Steps:
->pip3 install pyqt5.
->The view used for controller acknowledge what to perform. 
->The model process the query perform the task and then revert back the final answer.
->Controller helps to get user input and queries from model and then respond. 