# Lab 8 - Starter
## 1) In your own words: Where would you fit your automated tests in your Recipe project development pipeline?
 - Within a Github action that runs whenever code is pushed 
 - Manually run them locally before pushing code
 - Run them all after all development is completed

All three of these are acceptable options but we will more than likely be testing with github actions on successful merges.

## 2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
- No.

## 3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.
- No this affects too many things

## 4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.
- Yes this is appropriate for a unit test as it only affects the message length