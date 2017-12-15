Completed 31Aug2017

# PROJECT

Replicate a design mockup to create a responsive page, using HTML and CSS.


# SET UP INSTRUCTIONS

You will need:
Python3
Vagrant
VirtualBox

Setup:
Install Vagrant And VirtualBox
Clone this repository


# PROGRAM EXECUTION

1. Launch Vagrant VM by running vagrant up, you can the log in with vagrant ssh
2. To load the data, use the command psql -d news -f newsdata.sql to connect a database and run the necessary SQL statements.
    The database includes three tables:
        Authors table
        Articles table
        Log table
3. To execute the program, run python3 newsdata.py from the command line.
