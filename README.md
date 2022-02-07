# htaccessconfigs

This are .htaccess configs for Apache based servers, haven't really worked with Nginx yet, will update when I interact with them

## Tools
here are tools 

### to generate CSP headers
- [https://csper.io/generator](casper.io)
- [https://report-uri.com/home/generate](report-uri.com)

### Here is how you can test
- [https://observatory.mozilla.org/](https://observatory.mozilla.org/)
- [https://securityheaders.com/](https://securityheaders.com/)

### Test and submit your website for HSTS
- [https://hstspreload.org/](https://hstspreload.org/)

## More Reading

- [https://www.askapache.com/htaccess/](https://www.askapache.com/htaccess/)
- [http://zemalf.com/1076/blog-htaccess-rules/)](http://zemalf.com/1076/blog-htaccess-rules/)
- [https://perishablepress.com/stupid-htaccess-tricks/](https://perishablepress.com/stupid-htaccess-tricks/)


## NB
This settings are not set to work out of the box, customise to what seems fit
Disable or enable one by one when deploying, incase you break your site. This is after backing up your previous configs
Tweak and tune to your desire, happy hacking

As a performance precaution, Expires/ Cache Control Headers directives are not to be used together with Etags, use what suits you better
