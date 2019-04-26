install:
	virtualenv testing
	. testing/bin/activate
	pip install -r requirements.txt

jenkins_test:
	nosetests app/ -v
