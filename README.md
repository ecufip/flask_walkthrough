Simple blog application from Flask walkthrough. Not written in virtualenv.

# To run (from application folder):

$export FLASK_APP=application.py
$export FLASK_DEBUG=true
$flask run

or 

$export FLASK_APP=application.py; export FLASK_DEBUG=1; flask run

# To initialize db:

$flask initdb

# To test:

in /application run:

$ python tests.py
