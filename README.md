Hello everyone,

######About:
There's multiple things that makes DAws better than every Web Shell out there:
1. Bypasses Disablers; DAws isn't just about using a particular function to get the job done, it uses up to 6 functions if needed, for example, if `shell_exec` was disabled it would automatically use `exec` or `passthru` or `system` or `popen` or `proc_open` instead, same for Downloading a File from a Link, if `Curl` was disabled then `file_get_content` is used instead and this Feature is widely used in every section and fucntion of the shell.
1. Automatic Base64 Encoding; DAws base64 encodes automatically most of your GET and POST data using Java Script or PHP which will allow your shell to Bypass pretty much every WAF out there.
1. Advanced File Manager; DAws's File Manager contains everything a File Manager needs and even more but the main Feature is that everything is dynamically printed; the permissions of every File and Folder are checked, now, the functions that can be used will be available based on these permissions, this will save time and make life much easier.
1. Tools: DAws holds bunch of useful tools such as "bpscan" which can identify useable and unblocked ports on the server within few minutes which can later on allow you to go for a bind shell for example.
1. Everything that can't be used at all will be simply removed so Users do not have to waste their time. We're for example mentioning the execution of c++ scripts when there's no c++ compilers on the server(DAws would have checked for multiple compilers in the first place) in this case, the function would be automatically removed and the User would know.
1. Openned Source.

DAws was mainly created by dotcppfile and Aces because everyone was getting sick of all these Shells that were easily stopped by WAFs or Disablers or whatever. Something like DAws is really hard to stop because there's always a substitute for everything and the user doens't have to worry about it at all.
