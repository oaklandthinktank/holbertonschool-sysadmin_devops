0-iam_betty
Changes current user's username to betty

1-who_am_i
Prints effective userid of current user

2-groups
Prints current user's groups

3-new_owner
Changes owner of "hello" file to betty

4-empty
creates empty file "hello"

5-execute
Adds execute permission for owner of "hello"

6-multiple_permissions
Adds execute permission for owner and group owner of "hello", adds read permission for all others

7-everybody
Adds execute permission to "hello", for owner, group owner, and all other users

8-James_Bond
Sets permissions:
owner - no permissions
group owner - no permissions
all others - all permissions

9-John_Doe
Sets permissions of "hello" file to:
owner - read, write
group owner - read, execute
all others - write, execute

10-mirror_permissions
Sets permissions of "hello" file to match "olleh" file's permissions

11-directories_permissions
Adds execute permission for all, on all subdirectories of present working directory, while regular files are unaffected

12-directory_permissions
Creates directory "dir_holberton" with permissions:
owner - read, write, execute
group owner - read, write
all others - read

13-change_group
Changes group owner to holberton for file "hello"

14-change_owner_and_group
Changes owner to betty, group owner to holberton, for all files and directories in present working directory

15-symbolic_link_permissions
Changes owner of "_hello" file to betty, group owner changes to holberton

16-if_only
Changes owner of "hello" file to betty, ONLY IF owned by user guillaume