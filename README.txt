To open the application simply launch the .app file located at /App/dist/coffeegrindsize.app

Please see this GitHub repo developed by Chris Saterlee for OS X and Windows installation packages of the app:
https://github.com/csatt/coffeegrindsize/releases/tag/v1.0.0

Thanks a lot Chris !

---

Tested on Fedora 37 with system packages:

* python3-tkinter-3.11.1-1.fc37.x86_64
* tk-1:8.6.12-3.fc37.x86_64

Python Dependencies:

* matplotlib
* numpy
* pandas
* pillow
* tkinter

Installation:

	virtualenv venv
	source venv/bin/activate
	pip3 install -r requirements.txt

Run:

	python3 coffeegrindsize.py

