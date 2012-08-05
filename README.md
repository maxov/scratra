#Scratra
Scratra is a framework for [Scratch](http://scratch.mit.edu) remote sensor connections inspired by [Sinatra](http://sinatrarb.com). That's about it. The website used to exist but was demolished from lack of interest. You should take a look at the wiki instead.
###Put this in your catnip
```python
#first.py
from scratra import *

@start
def whenstart(scratch):
  print 'Hello, World!'
  
@broadcast('hi, scratra!')
def hi(scratch):
  print 'Hi, Scratch!'
  
run()
```
###And meow
```sh
python first.py
```