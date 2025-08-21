 # TO-DO-LIST
** To-Do List** -– A Python-based task manager where you can add, view, and remove tasks in a loop-driven menu using functions and if-else logic.
     
      #Step-by-step algorithm .<br>
      
Start — create an empty list to_do_list = [].<br>

Loop — begin an infinite loop to keep the menu running until the user quits.<br>

Show menu — print the TO-DO-LIST menu with options: Add (1), Remove (2), Show (3), Quit (4).<br>

Read choice — read user input for decision. Try to convert to integer; if conversion fails, print "enter a valid decision" and go back to step 3.<br>

If decision == 1 (Add task):<br>
a. Prompt: "enter task wants to add:".<br>
b. Read the task string, trim whitespace.<br>
c. Append the task to to_do_list.<br>
d. Print confirmation: Task :<task> added to the list successfully.<br>
e. Return to step 3.<br>

If decision == 2 (Remove task):<br>
a. Prompt: "enter a task wants to remove:".<br>
b. Read the task string, trim whitespace.<br>
c. If the task exists in to_do_list, remove it and print task:<task> removed successfully.<br>
d. Otherwise print task not found in the list.<br>
e. Return to step 3.<br>

If decision == 3 (Show tasks):<br>
a. If to_do_list has items, print them (preferably numbered).<br>
b. If empty, print no task found.<br>
c. Return to step 3.<br>

If decision == 4 (Quit):<br>
a. Print "GOOD BYE" (or similar).<br>
b. Exit the loop and end the program.<br>

If any other decision: print "enter a valid decision" and return to step 3.<br>

Repeat steps 3–9 until the user chooses Quit.<br>
