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