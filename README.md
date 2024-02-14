# joplin-nginx-deployment
Deployment files for joplin + nginx deployment in server

This deployment file is used to set up the nginx reverse proxy and joplin on the server using podman.

For those of you who are new to joplin + reverse proxy, this deployment file may be useful for your example.

This deployment uses self signed certificate, and you might want to use real SSL certificate for production deployment.

For complete tutorial on this deployment file, please read https://medium.com/@johanesmistrialdo/joplin-server-nginx-reverse-proxy-deployment-f8bdea9ea7cf

**Note that I committed credentials and IP in this repository; this is not a good practice, and you shouldn't follow that. I only do this to make the deployment simpler to learn and with dummy credentials.**