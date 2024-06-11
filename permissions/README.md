# Shell - Permissions

This project contains a series of scripts that manage and manipulate file permissions and ownership in Unix-based systems.

1. **0-iam_betty**: A script that switches the current user to the user `betty`.

2. **1-who_am_i**: A script that prints the effective username of the current user.

3. **2-groups**: A script that prints all the groups the current user is part of.

4. **3-new_owner**: A script that changes the owner of the file `hello` to the user `betty`.

5. **4-empty**: A script that creates an empty file called `hello`.

6. **5-execute**: A script that adds execute permission to the owner of the file `hello`.

7. **6-multiple_permissions**: A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

8. **7-everybody**: A script that adds execution permission to the owner, the group owner, and other users, to the file `hello`.

9. **8-James_Bond**: A script that sets the permissions of the file `hello` to `007`, meaning no permissions for the owner and group, and all permissions for others.

10. **9-John_Doe**: A script that sets the mode of the file `hello` to `753`.

11. **10-mirror_permissions**: A script that sets the mode of the file `hello` to be the same as the mode of the file `olleh`.

12. **11-directories_permissions**: A script that adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users, without changing regular files.

13. **12-directory_permissions**: A script that creates a directory called `my_dir` with permissions `751` in the working directory.

14. **13-change_group**: A script that changes the group owner to `school` for the file `hello`.

15. **14-change_owner_and_group**: A script that changes the owner to `vincent` and the group owner to `staff` for all files and directories in the working directory.

16. **15-symbolic_link_permissions**: A script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively. The file `_hello` is a symbolic link.

17. **16-if_only**: A script that changes the owner of the file `hello` to `vincent` only if it is owned by the user `guillaume`.
