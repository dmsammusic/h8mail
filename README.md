# h8mail
send mail using node mailer.

> ### prerequirement 
 > -if use gmail the 2FA should be alove for less secured apps . for mode ref visit node mailer npm doc
 

```sh
 const mailer = require("./main.js"); 
```
> Ex : mailer ("User EMail/From Mail","User Password/From/AccPassword)","Send to mail", "Sub", "text")

```sh 
mailer("abc@gmail.com","password@1234","xyz@abc.com","Test Subject"," Mail Text ")
```
