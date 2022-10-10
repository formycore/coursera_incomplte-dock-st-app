FROM node:lts
# copy the project files from the working directory
COPY . . 
#first dot is where we are so it out current directory and the second dot is in actualy directory of the container
# so we once build this up it will copy all the contents from the local working directory to over inside the container
# to get app installed we need 
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]