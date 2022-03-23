# Notebook
## MenuCLI
**menucli.py** is the main script which is like an entry window of the Notebook app. Here the **run()** function is run and it should display all the options the user is given. From there the user chooses which action s/he would like to take. The options are:
1. Display Notes
2. Search Notes
3. Add Note
4. Modify Note
5. Quit

### Display Notes
To display notes the Notbook class is called. It consists the list of notes and every one of them is being printed in order

### Search Notes
The Search Notes action is run using match method. It searches for the string in tags or memo if the note and returns **True** if the string is found and **False** in the opposite scenario.

### Add Note
The action simply referes to Notebook class which has the list of Notes and appends new Note object to this list(adding memo, tags(if needed), id and date)

### Modify Note
The node is called by text, tag, or id. If the note is found then the user can change tags or memo of the note and it will ne modified. All this data is string

### Quit
Simply quits the script