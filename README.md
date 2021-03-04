# Awesome-Books(Github-API-Book-List-and-View-App)

![GitHub repo size](https://img.shields.io/github/repo-size/quickgrid/Awesome-Books?style=flat-square)

## UPDATE: Seems something in github API changed as this longer works. Changing to appropriate API call should make the code work without requiring many changes.

This app uses github api to get data from a specifc user repo. Then it parses all the pdf links in them and show them in list. User can click on any book name to view it instantly.


## Live App:
https://awesome-books.firebaseapp.com/

## Sample Input:
user name: vhf

repo name: free-programming-books

directory name: free-programming-books.md

## Screenshot:
Type the github user name in user name section, then the repo name then the directory name or file name if its in root folder.

It uses github api to get the data from a user, a specific repo and its directory/file. Although I made it for reading books other types can be used modifying the regex a little bit. Also it can be adjusted to point to an url with text and its will find all the pdf links there and load it in the app. 

![alt text](screenshots/screen.png "screenshot")
