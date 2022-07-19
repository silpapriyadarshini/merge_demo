#DEV1

1. created github repository

2. cloned the repository

	git clone git@github.com:<REPOSITORY_NAME>.git

3. In the main branch, created a file merge_demo.py and saved the contents. (INFO)

4. added file in staging area.

	git add merge_demo.py

5. reviewed the file added.

	git status

6. commit staged file to the main branch

	git commit -m "Add initial demo file"

7. pushed change to remote repqository

	git push

8. created new branch feature/Dev1

	git checkout -b feature/Dev1

9. Changed lines in the merge_demo.py file.
	line 6 is: logging.basicConfig(level=logging.ERROR)
	line 8 is: logger.setLevel(logging.ERROR)

10. added file to staging area.
	git add merge_demo.py

11. git status
	
12. git commit -m "Add Dev1 changes for log level ERROR"

13. git push -u origin feature/Dev1

14. Created pull request in remote repository.

15. pulled recently merged file from main branch.
	git pull --rebase origin main

16. Opened file in VS Code. and set level logging.DEBUG

16. git add merge_demo.py
	git rebase --continue

17. git push --force

18. Created pull request in remote repository.

