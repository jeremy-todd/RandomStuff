ToDo List Code Plan

Variables and type needed:

Need a SQL DB called todo
columns:	id int; desc varchar(20); dueDate datetime; status varchar(11)

bool done //used to determine when the user is done working in the application

ToDoContext todoList //used for instantiating the todoList context



In Main:

Use a while loop to gather information from the user on if they want to add an item, update an item, or delete an item. default will display all items.

User can also display items that are pending, in progress, or completed only.


Methods:

Need a method to display all items or only selected items.

Need a method to gather user input and create a todoItem object or update a todoItem object and return for processing.


Other Notes:

include bad input processing by the user.