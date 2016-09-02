# PyGUI

We did *NOT* write any of the backend to this, that was all done by the amazing people at robotpy
(https://github.com/robotpy/pynetworktables2js)

This is our usage of this, hosted on github for ease of access between machines

To install, run `./install.sh`
Then, run `./tornado_server.py`

You will need python to run this.

Then, connect to `localhost:8000/index.html` in a browser.

To change the default robot IP (by default is `10.39.66.1`), change it in `config.json`. You can also change the port, then connect to `localhost:$port`


