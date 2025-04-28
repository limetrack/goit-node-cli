# Contact Management CLI App

This is a simple command-line application for managing contacts. It allows you to list, add, remove, and get contacts using a `contacts.json` file.

### How to use

Clone or download the repository to your local machine.
`npm install`

### Commands

1. List All Contacts
   `node index.js -a list`
2. Get a Contact by ID
   `node index.js -a get -i <id>`
3. Add a New Contact
   `node index.js -a add -n "Name" -e "email@example.com" -p "123-456-7890"`
4. Remove a Contact by ID
   `node index.js -a remove -i <id>`
