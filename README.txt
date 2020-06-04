For the tech demo, we've deployed our demo to AWS EC2.

MOST IMPORTANTLY:

Since Bootstrap is front-end only, I didn't see the need to create a VM for 'vagrant up' purposes, since the content is totally static.

There is a website that can be accessed, but for the demo purposes, it's identical to simply open the HTML files in a browser.

I believe this should be sufficient, considering we've shown we can create vagrant VMs in other assignments, and this does not need one.

OTHER NOTES:

-Since Bootstrap is a front-end only framework, our pages are simple static content being served by NGINX.

-No full-stack framework has been used, since none is needed to utilize Bootstrap.

-This would be fairly easily extended to add a full-stack dynamic service.

-The site is running on the free tier of EC2, on an Ubuntu VM.
