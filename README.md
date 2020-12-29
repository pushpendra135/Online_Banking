************************************About the Project*******************************

The project aims to develop a Online banking system that is user-friendly and multifunctional.

1. I have used two separate database files(.dat files) for storing the normal user's and joint account
   user's data. Two more database files also have been used for deleting the particular account.

2.Three types of login created: Individual user, joint account user,Admin.

3.Individual and joint Account holders have to pass through a login system to enter their accounts.
and they can also sign up.

4.The application possess password-protected administrative access,thus
preventing the whole management system from unauthorized access.

5. Once you login as Admin, you can be able to add, delete, modify, search for a
specific account details.6.Once the customer connect to the server, you get the login and password prompt.
After successful login, you get the menu for example:

-Deposit
-Withdraw
-Balance Enquiry
-Password Change
-View details
-Exit

6.once you login as a joint account holder, proper file locking is implemented. If you
want to view the account details then read lock is set else if you want to withdraw
or deposit then write lock is used to protect the critical data section.

7.Used socket programming – Server maintains the data base and service multiple clients
concurrently. Client program can connect to the server and access their specific account
details.

*****How to Run Project****
 
 1. Compile the server.c file using gcc server.c -o server

 2. Compile the client.c file using gcc client.c -o client

 3. Run the server file ./server

 4. Run the client file  ./client

 5. For admin login Purpose :-
    Username :nobody Password : password 
