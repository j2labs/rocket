r_simple
==============

r_simple is a Python library for interfacing with the `ViewText API
<http://viewtext.org/>`_

r_simple is licensed under the `Apache Licence, Version 2.0 <http://www.apache.org/licenses/LICENSE-2.0.html>`_


Using
-----

r_simple is used as a very basic walk through of how a Rocket
can be implemented. In this case, we pass one argument to a remote
API and receive the json response.

That looks like this:

::

    simple_rocket = ViewTest()
    rocket_response = simple_rocket.text.get("extension.fm")

Install
-------

Don't install this. It's meant for educational purposes only.

r_simple depends on Rocket being installed.
http://github.com/exfm/rocket

James Dennis <james@extension.fm>
