# mvc-nginx-integrated-microservices-v1.0


![Screenshot 2023-02-05 at 7 59 52 AM](https://user-images.githubusercontent.com/44409170/216820163-8cdb0f56-0b49-4e64-80ed-db78087fd750.png)


# Usecases:

1.	Caching static content for high throughput.
2.	Redirects the requests to desired webpages
3.	Nginx acts a middle man/reverse proxy to handle large amount of traffic for the application.
4.	Forwards requests to available servers, i.e nginx can act as a load balancer.
5.	Encryption/Decryption 



# Step-by-step

1. Install nginx

2. configure nginx port and static webpage:

"nginx.conf" file

2a. configure static webpage :

"mysite" folder

3. Start nginx

bin/nginx

4. nginx Service API:

http://localhost:8080/

5. Reloading nginx:

nginx -s reload
