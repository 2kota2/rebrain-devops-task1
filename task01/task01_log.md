## Task 1. Basic work with git

	git config --global user.name 'Uladzimir Minin'
	git config --global user.email 'uladzimir.minin@gmail.com'

	git init rebrain-devops-task1

>Initialized empty Git repository in C:/_Scripts/Rebrain/DevOps/01_git/process/rebrain-devops-task1/.git/

	cd rebrain-devops-task1/
	
	vim ngninx.conf
	echo "This repository contains the default nginx configuration file" > README.md

	git add README.md
>warning: LF will be replaced by CRLF in README.md.
>The file will have its original line endings in your working directory

	git commit -m "Added README.md file"
>[master (root-commit) 1a9cfc0] Added README.md file
>  1 file changed, 1 insertion(+)
>  create mode 100644 README.md

	git add nginx.conf
>warning: LF will be replaced by CRLF in README.md.
>The file will have its original line endings in your working directory

	git commit -m "Added nginx.conf file"
>[master 32f8dac] Added nginx.conf file
>  1 file changed, 85 insertions(+)
>  create mode 100644 nginx.conf

	git log
>commit 32f8dac4deae23139e1599f553a97cf3e7046aed (HEAD -> master)
> Author: Uladzimir Minin <uladzimir.minin@gmail.com>
> Date:   Fri May 6 15:53:29 2022 +0300

>    Added nginx.conf file

>commit 1a9cfc0707069af970df68d77df4d0ae9adba062
> Author: Uladzimir Minin <uladzimir.minin@gmail.com>
> Date:   Fri May 6 15:52:07 2022 +0300

>    Added README.md file


	git status
>On branch master
>nothing to commit, working tree clean