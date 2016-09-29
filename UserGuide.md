# User Guide

This is a draft user guide for v0.0

## Quick Setup

TO BE DECIDED

## Objective

TO BE ADDED

# Commands List

The following are the list of commands that are supported by the application.

## Help

Display a list of usable commands and their format when called.
Format: `help`

> Help is also shown if you enter an incorrect command e.g. `abcd`
 
## Adding a task: `add`
Adds a new task.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> for format
> and command restrictions
> HERE

Examples: 
* `Example here`
* `Example here`

Adds a recurring task.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`


## Listing all tasks : `list`
List all the task.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`

List only tasks that are done/undone.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`

List task that are due by a deadline.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`

List task that are due on a specific date.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`

List tasks by tags.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here

List taks by keyword.<br>
Format: `PUT SYNTAX HERE` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`

## Search for task: `search`
Search for a task using a keyword.<br>
Format: `search KEYWORD [MORE_KEYWORDS]`

> The search is case sensitive, the order of the keywords does not matter, only the name is searched, 
and task matching at least one keyword will be returned (i.e. `OR` search).

Examples: 
* `Example here`
* `Example here`

## Edit a task: `edit
Edit the specified task.<br>
Format: `edit INDEX` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`

## Deleting a task : `delete`
Deletes the specified task.<br>
Format: `delete INDEX`

> Deletes the task at the specified `INDEX`. 
  The index refers to the index number shown in the most recent listing.

Examples: 
* `Example here`
* `Example here`

Undo a deletion.<br>
Format: `undo` 
 
> Explaination
> HERE

Examples: 
* `Example here`
* `Example here`

## Clearing all entries : `clear`
Clears all entries.<br>
Format: `clear`  

## Exiting the program : `exit`
Exits the program.<br>
Format: `exit`  

## Saving the data 
Address book data are saved in the hard disk automatically after any command that changes the data.<br>
There is no need to save manually.

## Changing the save location (Change content)
Address book data are saved in a file called `addressbook.txt` in the project root folder.
You can change the location by specifying the file path as a program argument.<br>

> The file name must end in `.txt` for it to be acceptable to the program.
>
> When running the program inside Eclipse, you can 
  [set command line parameters before running the program](http://stackoverflow.com/questions/7574543/how-to-pass-console-arguments-to-application-in-eclipse).
