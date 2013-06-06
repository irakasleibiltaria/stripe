stripe
======

###stripe & flask example

Install:
``` bash
$ sudo apt-get install python-pip python-dev build-essential 
$ sudo pip install --upgrade pip 
```

``` bash
$ sudo apt-get install python-virtualenv
```

Create an environment:
```bash
$ mkdir myproject
$ cd myproject
OR
$ git clone https://github.com/irakasleibiltaria/stripe.git
$ cd stripe

$ virtualenv venv
```

```bash
$ . venv/bin/activate
```

```bash
$ pip install flask
$ pip install --index-url https://code.stripe.com --upgrade stripe
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
