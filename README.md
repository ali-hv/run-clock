# run-clock

<div style="text-align: center">
    <a href="https://github.com/Ali-Hosseinverdi/run-clock/blob/main/icon/1.png">
    <img src="https://github.com/Ali-Hosseinverdi/run-clock/blob/main/icon/1.png"/></a>
</div>

With this little library you can set time for running your code.

## Usage:
<h3>run_at:</h3>
  
This function takes 3 arguments in string type:
  
1. hour
2. minute
3. second

For example, we have a script that we want to run at 11:30:00 :

``` python
from runclock import run_at

run_at('11','30','00')
print('time to run !')
```

And at 11:30:00 , it will print the text.

<h4>remember to use '00' instead of '0' or '05' instead of '5'</h4>
  
The defaule value for minute and second is '00' , so you can don't give minute or second argument:
  
``` python
run_at('11')
print('Hi')
```
It will print the text at 11:00:00

or

``` python
run_at('11', '30')
```
It will print the text at 11:30:00

## Installation:
You can install with pip:
```
pip install runclock
```

or install from source:
```
git clone https://github.com/Ali-Hosseinverdi/run-clock
cd run-clock
python3 setup.py
```
