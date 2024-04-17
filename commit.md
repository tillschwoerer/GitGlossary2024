# Term Name

**Term**: `commit`

**Definition**: 	Confirms and saves the changes to the working environment. 
			Creates a 'save point' you can go back to.

**Example**:  Describe the scenario or provide an example where this Git term might be applicable.

 *you can start a new branch after commiting to a change and simply go back to the commit point if you don't like your 	changes. If you like your changes, commit before continuing to work.*

**Code Snippet**: If applicable, include a code snippet that demonstrates how the term is used in practice, and what are typical variants (e.g. mentioning the flags that are used).


git commit				*#opens a text editor that prompts for a commit message*

git commit -m "message"	*#message can be added directly*

git commit -m "title" -m "message"	#*more detailed version*

git commit --amend				*#make changes to most recent commit*

git commit -a -m "message"			*#Add all files and commit in one step*
