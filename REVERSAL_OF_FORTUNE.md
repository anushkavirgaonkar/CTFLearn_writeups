#### Our team of agents have been tracking a hacker that sends cryptic messages to other hackers about what he's doing. We intercepted the below message he sent recently, can you figure out what it says? He mentions his hacker name in it, that's the code you need. .nac uoy fi tIe$reveRpilF eldnah ym gnisu em egassem ,avaj yllacificeps ,gnidoc emos htiw pleh deen I ,deifitnedi tegrat txeN


Don’t scratch your head too much. By the name of the challenge, you get a hint that this has something to do with reversing.

Reverse the message and you will get his name. Use the simple python script
```
>>> str = " .nac uoy fi tIe$reveRpilF eldnah ym gnisu em egassem ,avaj yllacificeps ,gnidoc emos htiw pleh deen I ,deifitnedi tegrat txeN"[::-1]  
>>> print(str)
```  
to make things faster.
