# Manage-User-Identity-with-Asp-net-8
Manage the authenfication and the autorization in a site web developped with Asp net 8

This project illustrates how to use the Asp .net Identity system to manage users in a web site. 
Such as add users, add roles, add claims; attach roles to an user, attach claims to an user or a role;
restrict the right of an user, like to prohibit to access a menu according the user's role and his claim.

This project uses EntityFrameWork 8 to model the entites of the asp .net Identity 
and uses the Database Sqlite to store the user identity info.

To verify the project, begin by login: test@gmail.com and Passeword : Yrs45678$
You can then add users with different roles and claims, and then verify that if an user hasn't an admin role, 
he cann't access the menu Manager
