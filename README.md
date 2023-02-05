# mvc-nginx-integrated-microservices-v1.0


![Screenshot 2023-02-05 at 7 59 52 AM](https://user-images.githubusercontent.com/44409170/216820163-8cdb0f56-0b49-4e64-80ed-db78087fd750.png)


# Usecases:

1. Nginx acts a middle man/reverse proxy to handle large amount of traffic for the application.

2. Forwards requests to available servers, i.e nginx can act as a load balancer.

3. Encryption/Decryption (HTTP to HTTPS)

# Step-by-step

# 1. Install nginx

# 2. configure nginx port and static webpage

/usr/local/etc/nginx/nginx.conf

# 2a. configure static webpage in the mysite folder

# 3. Start nginx

bin/nginx

# 4. nginx Service API:

http://localhost:8080/

# 5. Reloading nginx:

nginx -s reload
