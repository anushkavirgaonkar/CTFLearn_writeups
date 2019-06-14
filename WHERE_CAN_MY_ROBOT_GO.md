#### Hint: Where do robots find what pages are on a website?
 Hint 2: What does disallow tell a robot?
 Hint 3: The flag is not 70r3hnanldfspufdsoifnlds
 
Web robots or web crawlers traverse through websites in a defined and automated manner. Every website has it's **robots.txt**. This page lists the pages within the website that are not allowed to be traversed by the web robots. They tell the robot where **not** to go.  

In this challenge, we get enough hints to tell us that the flag has to do something with **robots.txt**. We view the website's robots.txt by going to `websitename/robots.txt`, where website name is ctflearn.

After going to [https://ctflearn.com/robots.txt](https://ctflearn.com/robots.txt), we find that `/70r3hnanldfspufdsoifnlds.html` is disallowed. After visiting [https://ctflearn.com/70r3hnanldfspufdsoifnlds.html](https://ctflearn.com/70r3hnanldfspufdsoifnlds.html) we get the flag.
