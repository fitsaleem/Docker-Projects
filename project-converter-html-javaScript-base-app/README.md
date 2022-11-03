# To containerze this applcation follow these steps

# step 1

# first build the image 
# use this command for building a image and don't forget to . in last
# Be careful about that you are present in same reposrity where your file are present otherwise give the file path instead of .
docker build -t <image-name> . 
  
# step 2
  
# now hopefully your image is build now its time to create and run container using your image
  # use this command for running the container
  
  docker container run --name=converter-app -d -p 5050:80 <give-image-name or image-id>
  
