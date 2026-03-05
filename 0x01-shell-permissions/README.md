# 0x01-shell_permissions

This folder contains exercises focused on file and directory permissions, ownership, and related permission tasks using standard Linux commands.

## 📂 Structure
|File | Script	Description|
|:----|:-------------------|
|0-Change_your_user_to_road	| Change your current user to user road|
|1-Print_the_effect_userid	| Print the effective user ID of the current user|
|2_Prints_all_the_groups_the_current_user_is_part_of	| Print all the groups the current user belongs to|
|3-Change_the_owner_of_the_file	| Change the owner of a file |
|4-Create_an_empty_file_named_hello	| Create an empty file named hello.|
|5-Adds_execute_permission_to_the_owner_of_the_file_hello	| Add execute permission for the owner on file hello|
|6-Adds_execute_permission	| Add execute permission (general script)|
|7-Adds_execute_permission_cant_use_ugo	| Add execute permission without using ugo notation.|
|8-Create_a_script_that_changes_the_permissions_with_only_digits	| Change permissions using numeric mode only|
|9-Sets_the_mode_of_the_hello_to_-rwxr-x-wx	| Set the mode of file hello to -rwxr-x-wx|
|10-Sets_the_mod_of_the_file_hello_as_the_same_as_olleh	| Set file mode of hello same as olleh|
|11-Adds_execute_permission_to_all_subdirectories_of_the_current_directory	| Add execute permission recursively to all subdirectories|
|12-Creates_a_directory_called_dir_roadMap_with_the_following_permissions	| Create directory dir_roadMap with specific permission set|
|13-Change_the_group_owner_to_map_for_the_file_hello	| Change group owner of hello to map|
|14-Change_the_owner_to_road_and_the_group_owner_to_map	| Change both owner and group of a file|
|15-Change_the_owner_to_road_and_the_group_owner_to_map_for_symbolic_file	| Change owner and group on a symbolic link|
|16-Change_the_owner_of_the_file_hello_to_road_only_if_it_is_owned_by_the_user_map	| Change owner of hello only if it’s owned by user map|

All scripts are written in Bash and focus on Linux permission and ownership manipulation.

## Learning Objectives

- Practice changing user identity and printing effective user info

- Understand how to view and change group memberships

- Modify file and directory permissions using symbolic and numeric modes

- Manage ownership of files and symbolic links

- Apply permission changes recursively in a directory hierarchy
