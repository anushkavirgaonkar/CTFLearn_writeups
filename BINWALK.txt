#### Here is a file with another file hidden inside it. Can you extract it? https://mega.nz/#!qbpUTYiK!-deNdQJxsQS8bTSMxeUOtpEclCI-zpK7tbJiKV0tXYY

Download the image. After running `file` command on the image, we find out that it is a **png** file and not a **jpeg** file.  

```
$ file PurpleThing.jpeg
PurpleThing.jpeg: PNG image data, 780 x 720, 8-bit/color RGBA, non-interlaced
```
Rename the file
```
$ mv PurpleThing.jpeg PurpleThing.png
```
The challenge tells us that the file contains another file hidden inside it. Also, the name of the challenge is **binwalk**, which suggests us to use the command `binwalk`. Binwalk is a command which is used to find if embedded files are present within a file.

Install binwalk if not already installed by:
```  
# yum install binwalk
```




