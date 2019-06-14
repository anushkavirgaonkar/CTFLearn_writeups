####Okay, this one is pretty easy... but not necessarily. `D733432373937303734373666343730373937323733343b7644534`

The challenge name `otpyrc` is the reverse of `crypto`. This gives us an idea (although not an obvious one) to reverse the given string. 
Use this simple python script:
```
>>> str = "4354467b343337323739373037343666373437303739373234337d"[::-1]  
>>> print(str)
```  
to make things faster.

These are hex numbers. You know the drill by now, find the ASCII equivalent to get the flag.


