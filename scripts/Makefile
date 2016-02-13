SCRAPE_COMMAND = "python scrape.py"

scrape:
	. `pwd`/.env/bin/activate; python $(SCRAPE_COMMAND)

validate:
	echo "Not implemented!"

install:
	virtualenv .env --no-site-packages --distribute
	. `pwd`/.env/bin/activate; pip install -r requirements.txt

uninstall:
	rm -fr .env
