# Gmail-deleter

Getting started
---------------

This script will help you delete unnecessary emails on gmail. It will provide you with options to delete all emails, emails from certain category and emails from a certain user . It also has additional features for emptying trash, deleting spam emails, getting statistics for email size, or displaying frequency of sent/received emails to/from a certain user.


Prerequisites
-------------

 - Python
 - The [pip](https://pypi.python.org/pypi/pip) package management tool for Python
 - Access to Internet and a web browser
 - A Google account with Gmail account enabled
 - matplotlib for Python


Turn on Gmail API
-----------------

Follow the [instructions](https://developers.google.com/gmail/api/quickstart/python#step_1_turn_on_the_api_name)

Installation
------------

 - Optional: Create a virtual environment

 - Run:

   `pip install --upgrade google-api-python-client`


(Check requirements.txt for additional informations about requirements for installation)

Usage
-----

 - Copy json file generated from Gmail API to the repository directory


Run script inside *src* folder with:

`python gmail_deleter.py`

You can add extra options -s or --secret with a path to your "credentials.json" file.

`python gmail_deleter.py -s credentials.json`

The script provides the following options:
 - delete all messages
 - delete all messages from a certain category (i.e. Promotions, Forums, Social...)
 - delete all messages from a certain user
 - clear trash
 - clear spam
 - delete messages matching custom filter
 - download all messages matching filter
 - forward all messages matching filter

**WARNING:** All messages will be deleted permanently (**not** moved to **Trash**).
