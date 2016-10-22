# Github Users


GET User list with paging:  
https://api.github.com/users?page=1&per_page=10

GET User's details  
https://api.github.com/users/mojombo


The project is an Android application which aims to fetch list of Github users and their details.  
Its purpose is creating MVP arhitecture with tests.  
  
## Model 

* User
* UserList

## Presenter

* getUserList(int page)
* onUserClicked(username)
* getUserDetails(username)
* searchForUser(username)

## View

* showLoading()
* showEmptyList()
* showUserList()
* showUserDetails()

Steto  
http://facebook.github.io/stetho/  