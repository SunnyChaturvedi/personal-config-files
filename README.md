Personal Configurations for shell startup files, tmux configs, sublime builds etc


---------------------------------------------------------------
### Some Interesting Utilities
- lf

```
https://github.com/gokcehan/lf/wiki/Tutorial

install command -
set CGO_ENABLED=0
go install -ldflags="-s -w" github.com/gokcehan/lf
```

- Maccy 

```
https://github.com/p0deje/Maccy
```


---------------------------------------------------------------
### $PS1 cheatsheet (do `echo $PS1` to see yours)
 ![alt text](https://github.com/SunnyChaturvedi/personal-config-files/blob/main/PS1-codes-syntax-meaning.png)


Read more about $PS1 customization at - [Link](https://github.com/SunnyChaturvedi/personal-config-files/blob/main/PS1-config-guide.pdf)



---------------------------------------------------------------
### about /var/mail/

your output of crons is store in a single file here, usually the files name is your username

you can edit
```
/etc/mail.rc
```

to alter setttings
```
~ ❯ cat /etc/mail.rc
set append dot save ask crt
ignore Received Message-Id Resent-Message-Id Status Mail-From Return-Path Via
set noappend
set hold
```

* _noappend_ is to get the new mails at top

* _hold_ is to stop the read mails to be deleted

take from - [man mail(1)](https://www.commandlinux.com/man-page/man1/mail.1.html)
