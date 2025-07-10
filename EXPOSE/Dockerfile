#EXPOSE will give which ports are opened to the user, this is for inormation purpose only
#It also provides the documentation of who builds the image and who runs the container
FROM almalinux:8
RUN yum install nginx -y
EXPOSE 80/tcp
CMD ["nginx","-g","daemon off;"]