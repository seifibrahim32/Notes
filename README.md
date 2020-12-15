It is about MainActivity has a 
recyclerView with list of Notes so there is an option to let the 
user swipe if he needs to delete a note from the list.
After swiping a SnackBar appears to choose if he need to undo again.
Inside the Scenario ,it is stored in Database so it maintains the
way of storing data easily with Data Access Object (Dao) annotation.
In NoteActivity, the user is allowed to edit text and save it and at upper
right there is option to delete and while choosing the option, the dialog
appears whether if the user is sure about the operation or not.
So if yes it will close the dialog and the activity is terminated and return back to the MainActivity.java.
Otherwise it won't do something.
