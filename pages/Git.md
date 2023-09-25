- git pull 冲突
	- https://stackoverflow.com/questions/4157189/how-to-git-pull-while-ignoring-local-changes
	- 解决：
		- ```
		  git fetch --all
		  git reset --hard origin/master
		  git pull
		  ```
- git 改commit message
	- ```
	  git commit --amend --only -m 'xxxxxx'
	  ```
-