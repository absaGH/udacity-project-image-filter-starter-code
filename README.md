# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

## running the project
First, on the terminal type:
**npm install**

Then, run the project by typing:
**npm run dev**

Finally, you can test the end point via: (http://localhost:8082/filteredimage?image_url=https://dogtime.com/assets/uploads/2018/10/puppies-cover.jpg)
### original image:
![Original image](https://dogtime.com/assets/uploads/2018/10/puppies-cover.jpg)
### after applying filter:
![The filtered image](https://github.com/absaGH/udacity-project-image-filter-starter-code/blob/dev/deployment_screenshots/filteredimage.jpeg?raw=true)

## The deplopyed version

The Elastic Beanstalk App URL for the project:

(http://image-filter-api.us-east-1.elasticbeanstalk.com)

(http://image-filter-api.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://dogtime.com/assets/uploads/2018/10/puppies-cover.jpg)
