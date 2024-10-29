# Tor-Ip-correlation
This repo provide a simple server that is able to collect the IP of the user that are visiting the page, if the user visit the page with normal browser and tor browser, the server provider is able to correlate the IPs (user and tor user).
## Use case
If you black list the tor exit relay IPs with a message like "You cannot you this site on tor", the user will probably load the site with a normal browser, you can collect all the IPs and timestamp that you recive and correlate user looking on the timestamp of blur and focus.
