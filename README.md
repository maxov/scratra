#Scratra ~ Python-Scratch is no longer a pain
###Put this in your pipe:
```python
#test.py
from scratra import *

@broadcast('hi')
def hi(scratch):
  print 'Hello, world!'
  
run()
```
Download scratra.py.
Start scratch, enable remote sensor connections.
###Then smoke it
```bash
cd your_dir
python test.py
```
In scratch, make a broadcast called `'hi'` and run.   
You just saved yourself a _headache_.