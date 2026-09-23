# 0x01. Shell, permissions

Description of each script in this directory:

- `0-iam_betty`: switches the current user to the user `betty`.
- `1-who_am_i`: prints the effective username of the current user.
- `2-groups`: prints all the groups the current user is part of.
- `3-new_owner`: changes the owner of the file `hello` to the user `betty`.
- `4-empty`: creates an empty file called `hello`.
- `5-execute`: adds execute permission to the owner of the file `hello`.
- `6-multiple_permissions`: adds execute permission to the owner and group owner, and read permission to other users, on the file `hello`.
- `7-everybody`: adds execute permission for the owner, group owner, and other users, on the file `hello`.
- `8-James_Bond`: sets the file `hello`'s permissions so owner and group have none, and others have all.
- `9-John_Doe`: sets the file `hello`'s mode to `rwxr-x-wx`.
- `10-mirror_permissions`: sets `hello`'s mode to match `olleh`'s mode.
- `11-directories_permissions`: adds execute permission for owner, group, and others to all subdirectories of the current directory, without touching regular files.
- `12-directory_permissions`: creates a directory `my_dir` with permissions 751.
- `13-change_group`: changes the group owner of `hello` to `school`.
- `14-change_owner_and_group`: changes the owner to `vincent` and the group to `staff` for all files and directories in the working directory.
- `15-symbolic_link_permissions`: changes the owner and group of the symbolic link `_hello` itself to `vincent` and `staff`.
- `16-if_only`: changes the owner of `hello` to `vincent`, only if it is currently owned by `guillaume`.
