# Introduction #

This page documents how to configure your web server to add support for both HTC and SWF files. Feel free to edit this page if you have knowledge on how to do this for your particular web server environment.


# Details #

Apache 1.0 and 2.0
  * You can drop an [.htaccess](http://www.javascriptkit.com/howto/htaccess.shtml) file into the directory where the svg.htc and svg.swf files are located. This file would consist of the following:

```
AddType text/x-component htc
AddType application/x-shockwave-flash swf
AddType image/svg+xml svg
```

  * You can modify the full Apache configuration, generally at /etc/httpd/mime.types or /etc/mime.types. Add the following two lines and then restart your web server:

```
text/x-component htc
application/x-shockwave-flash swf
image/svg+xml svg
```