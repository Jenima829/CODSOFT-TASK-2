# CODSOFT-TASK-2
NAME : JENIFER Y
DOMAIN : PYTHON PROGRAMMING
TASK 2: TO-DO-LIST

INTRODUCTION:
This program is a To-Do List Application created using Python's Tkinter library. It allows users to manage a list of tasks with features to add, update, delete, and display tasks in a visually simple and intuitive interface. Here’s an overview of the components, technologies, and their functionalities:

Introduction to Tkinter
Tkinter Library: Tkinter is Python's built-in library for creating GUIs. This program uses it to build the main application window, buttons, entry fields, and list displays that enable users to interact with the to-do list.
Message Boxes: The messagebox module is used to show warnings to users when there’s an input or selection error (e.g., trying to delete a task without selecting one).
Core Functionalities
Adding Tasks:
->The add_task() function adds a new task to the list of tasks. It retrieves the input from the entry field, appends it to the tasks list, clears the entry field, and calls display_tasks() to refresh the list display.
Updating Tasks:
->The update_task() function allows users to modify an existing task. It gets the selected task's index from the listbox, replaces it with the new text from the entry field, and updates the display. If no task is selected, a warning message appears.
Deleting Tasks:
->The delete_task() function removes the selected task from the list. It uses the selected index to delete the task from tasks and updates the display. If no task is selected, it prompts a warning message.
Displaying Tasks:
->The display_tasks() function clears the listbox and populates it with the updated tasks list, ensuring that any new additions, updates, or deletions are shown in real-time.
GUI Elements

Listbox: A tk.Listbox widget displays the list of tasks. The listbox’s configuration allows for task selection, making it possible to update or delete specific tasks.
Scrollbars: A scrollbar is added to the listbox to accommodate long lists, allowing users to scroll through tasks.
Entry Field: An Entry widget lets users type new tasks or updated task descriptions.
Buttons: The application includes buttons to add, update, and delete tasks, each triggering the appropriate function.

Tkinter Main Loop
The root.mainloop() keeps the application window open and responsive until the user closes it. This loop continuously listens for and responds to user actions.

Overall Workflow
When the application starts, it displays an empty task list. Users can type a new task in the entry field and click "Add Task" to add it to the list. Selecting a task allows updating or deleting it as needed. The application refreshes the display whenever tasks are modified, ensuring users see the latest list of tasks in real-time.




<img width="443" alt="TD1" src="https://github.com/user-attachments/assets/9c104c16-4b8d-42ad-b8c8-120c63716363">

<img width="443" alt="TD2" src="https://github.com/user-attachments/assets/242f929d-e021-40cb-ac62-a46ce3310546">
<img width="319" alt="TD3" src="https://github.com/user-attachments/assets/b4bfe719-9ed5-4f52-9400-fd07df3607c6">
<img width="455" alt="TD4" src="https://github.com/user-attachments/assets/be8ba162-97b3-4e7a-a2fa-25946ec14c37">
