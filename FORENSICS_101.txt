#### Think the flag is somewhere in there. Would you help me find it? [https://mega.nz/#!OHohCbTa!wbg60PARf4u6E6juuvK9-aDRe_bgEL937VO01EImM7c](https://mega.nz/#!OHohCbTa!wbg60PARf4u6E6juuvK9-aDRe_bgEL937VO01EImM7c)
Download the image. Don’t go by what the image says. Most forensic challenges deal with viewing the **hexdump** of the image. The hexdump is the hexadecimal representation of the image. Use commands `hexdump` or `xxd` for this.

1. hexdump:  
`$ hexdump -C filename.jpg`  
This displays the input offset in hexadecimal, followed by sixteen space-separated, two column, hexadecimal bytes, followed by the same sixteen bytes in %_p format enclosed in “|” characters.

2. xxd:  
`$ xxd filename.jpg`  
You can pipe these commands with grep for better searching.

The flag is present in the hexdump of the file can will be visible after you execute these commands on the terminal/cmd.
