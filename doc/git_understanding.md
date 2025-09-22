1. install git

2. create remote branch

3. Setup Git on your machine
	git config --global user.name "Your Name"
	git config --global user.email "your-company-email@domain.com"

	Check:
	git config --list


4. Create local project and write code
git init

5. Commit your first code
	create main.py file
	git add main.py
	git commit -m "Initial commit: print 3 lines"


6. Link with GitHub and push
	git remote add origin https://github.com/YOUR_USERNAME/test_app.git
	git branch -M main
	git push -u origin main


7. Create branch for task task_change_message
	git checkout -b task_change_message


8. Change message and add 3 more lines
	Edit main.py file

9. Commit branch
	git add main.py
	git commit -m "task_change_message: updated messages and added 3 extra lines"
	git push -u origin task_change_message

    