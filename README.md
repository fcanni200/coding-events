## coding-evevnts

## Purpose of app

Organizing events by allowing users to create events with descriptions,
venue, number of participants, and registration requirements. 

## Current state of app

Currently the app is able to create, edit, save and delete an event. 

## Future improvements

The app needs a person class to be able to create a user account.
The person class will need the following properties: 
name(String)
username(String)
password(password)
dob(date)
contact info(Object)
gender(String)

method:
getters, setters, and toString and an empty constructor

possible support classes:
Contact info class (name, mailing address, email, phone number)
Account class (Account #, user Id, password, account preferences)
Friends class (User id, name)

Relationship between classes:
person /event: many-to-many
person /contact: one-to-many
person /account: one-to-one
person /friend: one-to-many