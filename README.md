edentest
========

Sahana Eden Test Cases for the Robot Framework

Instructions
------------

1. Install Robot Framework

        pip install robotframework
        pip install robotframework-selenium2library
        pip install robotframework-databaselibrary

2. Checkout Test Cases

        git clone https://github.com/nerdis/edentest.git

3. Configure Test Suite
  * go to the edentest directory
  * copy config.example.py into config.py
  * edit config.py and adapt the settings to your environment

4. Configure and start Sahana Eden
  * run clean script
  * populate the database
  * start web2py

5. Run tests

        pybot edentest

6. See results
  * open 'report.html' in your browser
