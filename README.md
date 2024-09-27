# QTM 350 - Quiz 01

## Instructions

Please complete the following tasks using command-line operations and Git
commands as covered in Lectures 02 to 06. Document all commands in a file named
`commands.txt` located in the repository's root directory. The final repository
on GitHub should reflect all changes made, and the `commands.txt` file should
contain a comprehensive list of all commands used throughout the project. You
may copy and paste the commands directly into the `commands.txt` file if
needed.

Please submit the link to your repository on Canvas or via email at
<danilo.freire@emory.edu>.

## Tasks

1. Fork this repository to your GitHub account and clone it to your local
   machine.
   
2. Change directory into the cloned repository and create a new branch named
   `feature-enhancements`.
   
3. Create a file named `commands.txt` in the root of the repository to document
   all commands used.
   
4. Create a new directory called `analysis` within the repository and inside
   it, create files `exploratory.ipynb` and `model_evaluation.ipynb` using a
   single command with brace expansion.

5. Add a new section to the `README.md` file with the heading "## Data
   Analysis". Stage and commit the changes with the message "Add data analysis
   section and notebooks".

6. Create a new directory named `models` and inside it, create files
   `baseline_model.py` and `improved_model.py` using a single command with
   brace expansion.

7. Move all `.txt` files from the `data` directory to a new directory named
   `text_data` using a single command with wildcards.
   
8. Modify the `.gitignore` file to exclude the `temp` directory and any files
   with the `.log` extension. Stage and commit the changes with the message
   "Update .gitignore and reorganize data".

9. Create a new file named `requirements.txt` in the root of the repository and
   add the following lines:
   
```markdown 
numpy==1.21.0
pandas==1.3.0 
```
   
10. Stage and commit the `requirements.txt` file with the message "Add
    dependencies file".
    
11. Rename the `src` directory to `source_code`.
    
12. Commit the renaming of the directory with the message "Rename src to
    source_code".
    
13. Update the `README.md` file to include a section about the project's
    license. The lines are available below. Stage and commit the changes with
    the message "Update README with license information".

```markdown
## LICENSE

This project is licensed under the MIT License. 
```
    
14. Create a new file named `LICENSE` with the same content as the section
    added to the `README.md` file.
    
15. Stage and commit the files with the message "Add license".
    
16. Merge the `feature-enhancements` branch into the `main` branch.
    
17. Push the updated `main` branch to your forked repository on GitHub.
    
18. Delete the `feature-enhancements` branch both locally and remotely.
    
19. Create a new branch named `docs-update` and switch to it.
    
20. Update the `README.md` file to include a section about the project's
    dependencies and how to install them using the `requirements.txt` file.
    Stage and commit the changes with the message "Update README with
    dependencies information".
    
```markdown
## Dependencies

To install the project dependencies, check `requirements.txt`.
```

21. Merge the `docs-update` branch into the `main` branch.
    
22. Push the updated `main` branch to your forked repository on GitHub.
    
23. Delete the `docs-update` branch both locally and remotely.
    
24. Create a new file named `quiz_completed.md` in the root of the repository.
    
25. Update the `commands.txt` file with all the commands used throughout the
    project, and commit it with the message "Document Git commands". Push the
    changes to the `main` branch on GitHub.

### Bonus Questions

1. Rebase the `feature-enhancements` branch onto the `main` branch.
   
2. Set up a Git alias named `git hist` that displays the commit history in a concise format.
   
3. Modify the `.gitignore` file to exclude files with the `.bak` extension and directories named `logs/` using a single command.

Good luck!
