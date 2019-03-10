# bWAPP

This is just an instance of the OWASP [bWAPP project](http://www.itsecgames.com/) as a docker container.

The container is based on [raesene/bwapp](https://hub.docker.com/r/raesene/bwapp/)

I have updated the LAMP version to fix the CAPTCHA challange that stopped working.

To launch the application, you should use:

```
docker run -d -p 8000:80 h0pp/bWAPP
```

(Note: I recommend using port 8000 to prevent right problems in ports under 1024).

and you should be able to go to <ip>/install.php to set up your instance.
