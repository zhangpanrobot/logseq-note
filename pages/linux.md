- [Manage file permissions on Unix-like systems](https://kb.iu.edu/d/abdb)
- | Access class | Operator | Access Type |
  | ---- | ---- | ---- |
  | u (user) | + (add access) | r (read) |
  | g (group) | - (remove access) | w (write) |
  | o (other) | = (set exact access) | x (execute) |
  | a (all: u, g, and o)| | |
- | Access class | permission |
  | ---- | ---- |
  | the user’s (owner’s) permissions | -**rwx**r-xr-x |
  | group members’ permissions | -rwx**r-x**r-x |
  | others’ permissions | -rwxr-x**r-x** |
- ![Diagram of the components in chmod](https://www.pluralsight.com/content/dam/pluralsight2/b2c-blog-files/seo-refresh/linux-file-permissions/Linux-File-Permissions-2.webp)
- 0 = No Permission
- 1 = Execute
- 2 = Write
- 4 = Read
- | Binary | Octal | Permission |
  | ---- | ---- | ---- |
  | 000 | 0 | — |
  | 001 | 1 | –x |
  | 010 | 2 | -w- |
  | 011 | 3 | -wx |
  | 100 | 4 | r– |
  | 101 | 5 | r-x |
  | 110 | 6 | rw- |
  | 111 | 7 | rwx |
- Each number for each access class
	- 700 will give read, write, and execute permissions for the user only
	- 777 will give read, write, and execute permissions for everyone
- 面试
	- 熟悉linux操作系统
		- [openssh升级方案](https://www.zhihu.com/question/517101428/answer/3041079679)
		- \todo 123
		-