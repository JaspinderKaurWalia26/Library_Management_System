# Library Management System


![c0b13e6659629 56027c9435d35](https://github.com/JaspinderKaurWalia26/Library_Management_System/assets/132120070/6766552f-a9a3-4e2c-a92f-a34043f43063)

The Library Management System based on frappe framework,in which the Librarian can log in and manage Articles and Memberships. We will build the following models:

1. Article: A Book or similar item that can be rented.
2. Library Member: A user who is subscribed to a membership.
3. Library Transaction: An Issue or Return of an article.
4. Library Membership: A document that represents an active membership of a Library Member.
5. Library Settings: Settings that define values like Loan Period and the maximum number of articles that can be issued at a time.

The Librarian will log in to an interface known as Desk.The Desk provides many standard views like List view, Form view, Report view, etc, and many features like Role-based Permissions.

**Lets get started**

Go to terminal and change the directory by using command -cd frappe-bench

##  Create An App 
 Command- bench new-app library_management

 After implementing this command you will be prompted with the details of your app and app named library_management will be created in the apps folder.

 
##   Create A Site
 Command- bench new-site library.test
 

##   Install App On Site
 Command - bench --site library.test install-app library_management

##   Create A Doctype 
 Before we create doctype, we need to enable developer mode on our bench .
 
 For that follow command - bench set-config -g developer_mode true

 Then bench start

 


 

 

