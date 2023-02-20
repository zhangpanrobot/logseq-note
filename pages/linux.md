- [Manage file permissions on Unix-like systems](https://kb.iu.edu/d/abdb)
- | Access class | Operator | Access Type |
  | ---- | ---- | ---- |
  | u (user) | + (add access) | r (read) |
  | g (group) | - (remove access) | w (write) |
  | o (other) | = (set exact access) | x (execute) |
  | a (all: u, g, and o)| | |
- | Access class | permission |
  | the user’s (owner’s) permissions | -**rwx**r-xr-x |
  | group members’ permissions | -rwx**r-x**r-x |
  | others’ permissions | -rwxr-x**r-x** |
- ![Diagram of the components in chmod](https://www.pluralsight.com/content/dam/pluralsight2/b2c-blog-files/seo-refresh/linux-file-permissions/Linux-File-Permissions-2.webp)
- Permission numbers are:
- 0 = ---
- 1 = --x
- 2 = -w-
- 3 = -wx
- 4 = r-
- 5 = r-x
- 6 = rw-
- 7 = rwx
  each number for each access class;
- 700 will give read, write, and execute permissions for the user only
- 777 will give read, write, and execute permissions for everyone.