stripe
======

###stripe & flask example

Install flask python stripe:
``` bash
$ sudo apt-get install python-pip python-dev build-essential 
$ sudo pip install --upgrade pip 
$ sudo pip install --index-url https://code.stripe.com --upgrade stripe
$ sudo pip install flask
```

To execute application:
``` bash
$ PUBLISHABLE_KEY=pk_test_... SECRET_KEY=sk_test_... python app.py
```

Use:

``` html
Embedded Form:
http://server/

Custom Form:
http://server/customform
