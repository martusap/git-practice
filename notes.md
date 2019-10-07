The very first time you use a computer
--------------------------------------

    git config --global user.name "April Martus"
    git config --global user.email "apmartus8@gmail.com"

Once every new project, in the project folder
----------------------------------------------

    git init

Every time I want to know what step im on 
------------------------------------------

    git status

three step commiting proccess
------------------------------
* Make code changes, saved and run -> no errors
* add code changes to the stage
    git add file_that_changes.rb
* Commit changes
    git commit -m "My commit message"

Show history
------------

    git log

To Submit to GitHub
-------------------
* First will have to create a ner repsoitory
* Copy git remote code into terminal
* push the code
    git push - will have to type in username and pasword

To work at home
---------------
* Open file on GitHub and copy link at the top
* clone the file 
    git clone (link)
* Push your edits from home to GitHub
* Back at school pull from edits
    git pull
