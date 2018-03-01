### Witty Errors ###
Text taken from here [here](https://error.gmdianaty.com)

A small project written by myself with humor from OrionNexus that simply replaces all those boring old Apache or NGINX error messages with much less agrivating screens that are in the Solarized color palete, complete with jokes and detailed explinations for end users.

Written with Boostrap.

The errors supported at this time as are follows:
```
Error 401 - Login Required
Error 402 - HOW DID YOU GET HERE
Error 403 - Access Denied from Server
Error 404 - Page Not Found
Error 500 - Unknown Server Error
Error 503 - Service Denial due to Unavailability
```

If you want, you can host it locally. Just edit your .htaccess and your home free. You can download it at the GitHub repository where you are right now.

Or if your lazy like me, you can just use the version I'm hosting here on my domain. Below is what you should replace your .htaccess file's error list with. Just delete the old one and paste this at the bottom:

```
###
BEGIN WITTY ERRORS LIST
REMEMBER: REMOVE ALL OTHER ERROR MESSAGE REFERALS HERE, BECAUSE IF YOU DONT YOUR GONNA GET AN ERROR WE DONT HAVE A WITTY PAGE FOR.
###
ErrorDocument 400 https://error.gmdianaty.com/400
ErrorDocument 402 https://error.gmdianaty.com/402
ErrorDocument 401 https://error.gmdianaty.com/401
ErrorDocument 403 https://error.gmdianaty.com/403
ErrorDocument 404 https://error.gmdianaty.com/404
ErrorDocument 500 https://error.gmdianaty.com/500
ErrorDocument 503 https://error.gmdianaty.com/503
###
END WITTY ERRORS LIST
###
```



