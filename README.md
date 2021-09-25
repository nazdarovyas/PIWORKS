# P.I. WORKS, USER MANAGEMENT PAGE DESING

Enabled users should be listed the User Management interface. Sorting and filtering should be done on the data in the columns. When the "Hide Disable User" button on the top of the table was unchecked, all users including the users who were disabled should be listed. 

An example table structure is given below.

[**+ New User**](NEWUSERPAGE) :ballot_box_with_check: Hide Disable User 


| ID :arrow_up: :flashlight: | User Name :arrow_up_down: :flashlight: | Email   :arrow_up_down: :flashlight: | Enabled :arrow_up_down: :flashlight: |
| --------------- | -------------------------------------- | ------------------------------------ | ------------------------------------ |
| 1               | Admin User                             | admin@piworks.net                    | true                                 |
| 2               | Test User                              | testuser@piworks.net                 | true                                 |


## ADD NEW USER PAGE

With the "New User" button, the right side of page new user addition form should be opened. 

An example of the form is given below.

- Regex control should be done for Email and Phone information. 
- The user role must be selected from the dropdown list. 
- By default, the form should be opened with the Enable option unchecked. 
- After filling in the fields, the "Save User" button at the top of the form should complete the registration process. 

### NEW USER FORM

[**Save User**](saveUser)

- Username:            _____

- Display Name:        _____

- Phone:               _____

- Email:               _____

- User Role:           _____ <ul><li>Guest</li><li>Admin</li><li>SuperAdmin</li></ul>
 
Enable: :white_large_square:

After the registration process is completed, the new user should be listed in the list on the left.