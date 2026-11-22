# Templates for prompts
Context: #file:SPEC.md #file:PROGRESS.md
Task: tell the AI the next step [example: implement F1 ] specify the feature from SPEC.md in Details
Details:
[Examples: 
- Save the array every time a pair is added.
- Load it when the page starts and show the list.]
Constraints: check the sections acceptance criteria and out of scope in the SPEC.md, adapt as you see fit 
[example: Only change script.js. Don't touch the HTML or CSS.]
Done when: define the condition(s) and requirements to fulfill the task


# empty template 
Context: #file:SPEC.md #file:PROGRESS.md
Task: 
Details:
Constraints: 
Done when: 

# Good vs. bad prompts examples
# Don´t "make it better"
"Better" means nothing; Copilot will change random things.
# Do instead 
"The list items are hard to read. Add spacing between them and make the German word grey. Only change style.css."
# Don´t "It doesn't work."
Copilot has to guess what's wrong.
# Do instead
"When I click Add, nothing appears in the list. The console shows: TypeError: list is null at script.js:12. Expected: the new pair appears."
# Don´t "Add delete and practice mode and a score counter."
Three features in one step
# Do instead
One prompt per feature, with a test in betwenn