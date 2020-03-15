# Training with Python Ninja Hebi

Author hebi@python-ninja.com

><span style="font-size:larger;">Even a python ninja has to find a solution to everyday tasks   
>before the way is clear to the ultimate wisdom.</span>

## Task 1 - Delete all files with extension '.doc' in a folder

There are different ways to reach the goal. But you can not do it with only one command.


```python
import os
folder = '/example_path/'
for file in os.listdir(folder):
    if file.endswith('.doc'):
        os.remove(folder + file)
```


```python

```
