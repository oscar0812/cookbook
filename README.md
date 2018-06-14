Todo:
  - finish section on github

To add beautiful code images use [this](https://carbon.now.sh/?bg=rgba(174,195,171,0)&t=seti&l=application/json&ds=false&wc=true&wa=true&pv=2px&ph=1px&ln=true)

To cite use [this](http://www.easybib.com/cite/)

To convert docx to pdf with working table of contents links use [this](https://online2pdf.com/convert-docx-to-pdf)


To update database:
  - go to phpmyadmin & select db you want to change
  - delete the old database
      - click Operations tab and click "Drop the database (DROP)"
        under Remove database section
      - Confirm by clicking ok
  - create a new database with the same name as the database you just deleted
      - Click New
      - Fill in the name input box
      - Click create
  - import the sql file
      - Click import tab
      - Click choose file and select the SQL file (should be in data/ directory)
      - Scroll down and click Go
  - Go back to project (cd with terminal) and run composer dump-autoload -o
