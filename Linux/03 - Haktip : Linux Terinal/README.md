# Linux Terminal 101

## [0 - Getting Started](https://www.youtube.com/watch?v=b5NmtmNwMgU&t=0s&index=2&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- `date`
- `cal` : calendar
- `free` : show the current free memory amount1
- `cd ~username` : go to `/home/username`

## [4 - type, which, and apropos](https://www.youtube.com/watch?v=CQvkF4LHY58&t=0s&index=6&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)
 
There is 8 section for man pages.
- `whatis` = `man -f`
- `info` : give more informations about a specific command.

## [7 - Redirecting Standard Terminal Errors in Linux](https://www.youtube.com/watch?v=faTXIBdZt-0&t=0s&index=9&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- `stdin` < 0
- `stdout` < 1
- `stderr` < 2
- `&` : both `stdout` + `stderr`

## [10 - How to use echo](https://www.youtube.com/watch?v=FYJVlTQYvNY&t=0s&index=12&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- `echo ~` : output `/home/username`
- `echo $((2 + 2))` :  output 4

## [11 - Using Expansions Commands in the Linux Terminal Part 2](https://www.youtube.com/watch?v=cQHua6LPLyc&t=0s&index=13&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- `echo $(ls)` :  output the result of `ls`
- `find $(ls /usr/bin* | grep zip)` or for example : 
```bash
ls -l `which cp` 
```
## [13 - Your Favorite Tips and Tricks](https://www.youtube.com/watch?v=klP_Ik9NN7o&t=0s&index=15&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- to unalias --> put `\` before the command

## [14 - My Top Best Resources](https://www.youtube.com/watch?v=HT9I6nlsXzM&t=0s&index=16&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- [commandlinefu.com](https://www.commandlinefu.com/commands/browse)
- [unixref.pdf](https://files.fosswire.com/2007/08/fwunixref.pdf)

## [15 - Typing Less with Keyboard Shortcuts](https://www.youtube.com/watch?v=b2l-Zz_m-W0&t=0s&index=17&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)
> **Remind** : try on another terminal

## [16 - How to Use History](https://www.youtube.com/watch?v=zNelCx81TJA&t=0s&index=18&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- `!1` : run the first command of `history`

## [18 - How to Change Your Identity](https://www.youtube.com/watch?v=lQ4ycCA7FOQ&t=0s&index=20&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)
- `id`
- `sudo -l` : show you how you can currently do

## [20 - Controlling Processes](https://www.youtube.com/watch?v=XUhGdORXL54&t=0s&index=22&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)
- `pstree` : display a tree of processes
- `vmstat` : report virtual memory statistics
- `tload` : graphic representation of system load average

## [22 - Viewer Tips Part 2!](https://www.youtube.com/watch?v=moOmrFc6J50&t=0s&index=24&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)

- `uname -r` : Kernel version
- `cat /etc/*release` : Distro version

- [Learn Linux The Hard Way](https://archive.is/xDb8o)

# Linux Terminal 201

## [23 - How to Configure Startup Files](https://www.youtube.com/watch?v=smCYN7o7OXk&t=0s&index=25&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [24 - Getting Started with Vi](https://www.youtube.com/watch?v=kI2naD_9WKg&t=0s&index=26&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [25 - Customize The Shell Prompt](https://www.youtube.com/watch?v=_kSCpNqKJbM&t=0s&index=27&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [26 - Installing and Updating Packages](https://www.youtube.com/watch?v=EJgXqQvqaIM&t=0s&index=28&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [27 - Working with Storage Media, ISO Images, and MD5 Checksums](https://www.youtube.com/watch?v=ZA5KMyuj5jk&t=0s&index=29&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [28 - Apt vs Apt-Get](https://www.youtube.com/watch?v=9jNcjdQxEV8&t=0s&index=30&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [29 - Networking Commands You Should Know!](https://www.youtube.com/watch?v=F1geJWP4Yvs&t=0s&index=31&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [30 - Networking Commands You Should Know Pt 2!](https://www.youtube.com/watch?v=RrmWU_Hg9e4&t=0s&index=32&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [31 - ifconfig vs ip](https://www.youtube.com/watch?v=XiERevpBTAk&t=0s&index=33&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [32 - How To Use Man Pages](https://www.youtube.com/watch?v=BWLSqZZfKc4&t=0s&index=34&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [33 - How To Use tar, gzip, bzip2, and zip](https://www.youtube.com/watch?v=f8-7lhs4ky0&t=0s&index=35&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [34 - Searching and Locating Files](https://www.youtube.com/watch?v=paFtuRv4Fc0&t=0s&index=36&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [35 - How To Use Grep!](https://www.youtube.com/watch?v=KhCn_NwxmSo&t=0s&index=37&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [36 - Grep and Metacharacters](https://www.youtube.com/watch?v=xXo1L28Jc6A&t=0s&index=38&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [37 - Using Brackets with Grep](https://www.youtube.com/watch?v=sQNvg-zTEvA&t=0s&index=39&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [38 - What is POSIX in Unix?](https://www.youtube.com/watch?v=U0GbJtnfqSM&t=0s&index=40&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [39 - Using the Find Command!](https://www.youtube.com/watch?v=JYR_s4TIWSM&t=0s&index=41&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [40 - Using the Find Command Pt 2](https://www.youtube.com/watch?v=WuZYqiais54&t=0s&index=42&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [41 - Monitoring System Resources Pt 1](https://www.youtube.com/watch?v=xcR_FjAy1HI&t=0s&index=43&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [42 - Monitoring System Resources Pt 2](https://www.youtube.com/watch?v=fwMTD9ghC3c&t=0s&index=44&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [43 - How To Use ExFAT In Linux](https://www.youtube.com/watch?v=40DghDGuljQ&t=0s&index=45&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [44 - How to Use Cat, Sort, and Uniq](https://www.youtube.com/watch?v=bH1BDBzc3I0&t=0s&index=46&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [45 - How to Use Cut, Paste, and Join](https://www.youtube.com/watch?v=k014CkDmB2A&t=0s&index=47&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [46 - How to Use Comm, Diff, and Patch](https://www.youtube.com/watch?v=yIU92YySlW0&t=0s&index=48&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [47 - How to Use tr, sed, and aspell](https://www.youtube.com/watch?v=F7Brrn-L1Zg&t=0s&index=49&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [48 - How to Use nl, fold, and fmt](https://www.youtube.com/watch?v=BksWPx-C8rg&t=0s&index=50&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [49 - How to Use pr and printf](https://www.youtube.com/watch?v=aLypSBf1TBY&t=0s&index=51&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [50 - Document Formatting with Groff](https://www.youtube.com/watch?v=NW5ZWN2b4zw&t=0s&index=52&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)


## [51 - How to Compile Source Code](https://www.youtube.com/watch?v=kMmmvhl_kzo&t=2s&index=53&list=PLW5y1tjAOzI2ZYTlMdGzCV8AJuoqW5lKB)
