# Overview

This script pulls down a user's Reddit comment history in JSON format.

To run under OAuth2, you will need provide two pieces of information
(username and password), and also register a Reddit AppID and "secret key"
per the following:

- https://github.com/reddit-archive/reddit/wiki/OAuth2-Quick-Start-Example

To run the script, pass the four tokens as follows:

./reddit-hist.py --user mzieg --password foo --app bar --secret baz
