# README
## HAPPY HOME
* It is a accomadation management system which can be used by accomadation management system and their users too.
* It has two user flows: admin and user

### REGISTRATION

* Registeration includes inputs like username,email,batch number,mobile,password and confirm password.
* All inputs fields are mandatory
* Username should contain only letters in it with 3 to 15 characters.
* Email should contain @ and . in it which should be in an email format.
* Password has been done with password digest.
* Password should contain minimum 8 characters and maximum 12 characters.
* Confirm Password and Password should be same and equal.
* If these matches correctly the user will be redirected to the main page.
* All the details are stored in the table name "Users".

### LOGIN PAGE

* All the input fields are manadatory to login in the account.
* Email and Password should be registered already in the localstorage if it doesn't match the user is asked to create a
account
* Both the fields should match to the details already stored even anyone of the field doesn't match the error will be
shown as a message.
* If all the fields are matched correctly the user will be redirected to the main page.
* All the details are stored in local storage.

#### User flow

##### feature 1 : Filter

* In the Pg page there will be a filtering options.
* Onclicking the filter options.It will filter by the options we clicked.

##### feature 2 : Location

* In the Pg page there will be a search bar.
* Onclicking the search bar and enter the location it will give the location pg that enetred.

##### feature 3 : Shortlist 

* In all page the shortlist page will appear if we logined.
* Onclicking the shortlist page they can see the liked pg they  have liked.