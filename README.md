# Creating_Node.JS_Project_with_npm
- open a new Directory Project
- open with VS Code
- open a new file app.js
- open a new terminal
# Commamnds
- npm init
- package name: (project) npmproject
- version: (1.0.0) 1.0.0
- description: Project
- entry point: (app.js)
- test command:
- git repository:
- keywords:
- author:
- license: (ISC)
# package.json Created
- {
  - "name": "npmproject",
  - "version": "1.0.0",
  - "description": "Project",
  - "main": "app.js",
  - "scripts": {
    - "test": "echo \"Error: no test specified\" && exit 1"
  - },
  - "author": "",
  - "license": "ISC"
- }
# Add--> "start": "node app.js"  --> under test line. New look below:
- {
  - "name": "npmproject",
  - "version": "1.0.0",
  - "description": "Project",
  - "main": "app.js",
  - "scripts": {
    - "test": "echo \"Error: no test specified\" && exit 1",
    - "start": "node app.js"
  - },
  - "author": "",
  - "license": "ISC"
- }
# Write--->  console.log("Test");  --> in app.js , then execute 
- Command: node app.js
- Test printed
# Execute npm
- Command: npm start
# Success !!
- > npmproject@1.0.0 start
- > node app.js

- Test
