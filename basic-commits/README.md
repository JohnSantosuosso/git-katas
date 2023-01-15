# Git Kata: Basic Commits
This kata will introduce you to the `git add` and `git commit` commands.

This is a very introductory kata. if you have used `git status`, `git log --oneline --graph`, `git add` and `git commit` extensively you should probably skip it.

You can look at the bottom of this file, if you have not yet done basic git configuration.

## Setup:

1. Run `source setup.sh` (or `.\setup.ps1` in PowerShell)

## The task

1. Use `git status` to see which branch you are on.

<img width="738" alt="Screen Shot 2023-01-15 at 12 42 34 PM" src="https://user-images.githubusercontent.com/95776577/212557659-c40d3de9-f393-4f22-95ad-eba10a357cf2.png">

3. What does `git log` look like?

<img width="898" alt="Screen Shot 2023-01-15 at 12 44 03 PM" src="https://user-images.githubusercontent.com/95776577/212557897-4b742565-af0d-4643-b5f9-73fc5f55e004.png">


5. Create a file
6. What does the output from `git status` look like now?

<img width="891" alt="Screen Shot 2023-01-15 at 12 45 32 PM" src="https://user-images.githubusercontent.com/95776577/212557889-939b5104-ca93-4dd4-8b2d-9170db7c4196.png">


7. `add` the file to the staging area
8. How does `git status` look now?
9. `commit` the file to the repository
10. How does `git status` look now?

![image](https://user-images.githubusercontent.com/95776577/212558022-b032213d-35df-45a7-b8c4-2a7fe1c630af.png)


12. Change the content of the file you created earlier
13. What does `git status` look like now?
15. `add` the file change
16. What does `git status` look like now?

<img width="893" alt="Screen Shot 2023-01-15 at 12 55 13 PM" src="https://user-images.githubusercontent.com/95776577/212558356-9389558e-56f3-4035-b5b9-08f48b9bd2d1.png">


18. Change the file again
19. Make a `commit`
20. What does the `status` look like now? The `log`?

<img width="882" alt="Screen Shot 2023-01-15 at 12 56 22 PM" src="https://user-images.githubusercontent.com/95776577/212558411-fa94c583-2163-48b3-b014-db32a761c5b2.png">


22. Add and commit the newest change

## Useful commands
- `git add`
- `git commit`
- `git commit -m "My commit message"`
- `git log`
- `git log -n 5`
- `git log --oneline`
- `git log --oneline --graph`
- `touch filename` to create a file (or `sc filename ''` in PowerShell)
- `echo content > file` to overwrite file with content (or `sc filename 'content'` in PowerShell)
- `echo content >> file` to append file with content (or `ac filename 'content'` in PowerShell)


## Git Initial Configuration
1. `git config --global user.name "John Doe"`
1. `git config --global user.email "johndoe@example.com`

For the vim scared:
- `git config --global core.editor nano`

For the windows peeps:
- `git config --global core.editor notepad`

Other editor options:
- `git config --global core.editor "atom --wait"`
- `git config --global core.editor "code --wait"`
- `git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst"`
