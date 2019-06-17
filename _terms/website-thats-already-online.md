---
title: Website That’s Already Online
lookup: website-thats-already-online
---
Certbot is usually meant to be used to switch an existing HTTP site to work in HTTPS (and, afterward, to continue renewing the site’s HTTPS certificates whenever necessary). Some Certbot documentation assumes or recommends that you have a working web site that can already be accessed using HTTP on port 80. That means, for example, that if you use a web browser to go to your domain using http://, your web server answers and some kind of content comes up (even if it’s just a default welcome page rather than the final version of your site). Some methods of using Certbot have this as a prerequisite, so you’ll have a smoother experience if you already have a site set up with HTTP. (If your site can’t be accessed this way as a matter of policy, you’ll probably need to use DNS validation in order to get a certificate with Certbot.)