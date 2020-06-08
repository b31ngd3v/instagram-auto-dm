Instagram Auto DM
========
<a href="https://www.instagram.com/sinha.py/"><img src="https://cdn.thenewstack.io/media/2017/06/eabeb0f2-f897a954-instagramheartspython.jpg" alt="Auto DMer"/></a>

## Before Running `DMer.py`

* Open DMer.py File and Edit The Following Lines:

1) `username = 'USERNAME'  # Enter your username here` [line:26]

2) `password = 'PASSWORD'  # Enter your password here` [line:27]

3) `timee = "21:44"  # Specific Time When The message will be send` [line:93]

4) `txt_box.send_keys(f"Hi @{usrnames} ! What's up ?")  # Messege that you want to send` [line:55]

5) `usrnames = ['psinha_09', 'sinha.py']  # List of users to whom you want to send messages` [line:13]


Ensure that you have Chrome installed and the
[`chromedriver` ](https://chromedriver.chromium.org/downloads) that matches
your Chrome version available on your `$PATH`. You may have to update this from time to time.

## Requirements
 
* [Python](https://www.python.org/)
* `python` on the PATH
* [The Requests Library](http://python-requests.org) for Python: `pip install requests`
* Install Selenium:

```bash
pip install selenium
```
* Install Schedule:

```bash
pip install schedule
```

## Run

* Run the programme using:

```bash
python DMer.py
```
