# JS-GUI

We did *NOT* write any of the backend to this, that was all done by the amazing people at robotpy
(https://github.com/robotpy/pynetworktables2js)

This is our usage of this, hosted on github for ease of access between machines

To install, run `./install.sh`
Then, run `./tornado_server.py`

You will need python to run this.

Then, connect to `localhost:8888/index.html` in a browser.

To change the default robot IP (by default is `10.39.66.1`)
To change the website port, run `./tornado_server.py -p $port`
to change robot, run `./tornado_server.py --robot $IP`
