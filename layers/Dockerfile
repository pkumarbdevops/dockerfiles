FROM almalinux:8
RUN yum install nginx -y
RUN echo "Hello, Welcome to Dockerfile. A way of creating own images" > /usr/share/nginx/html/hello.html
RUN yum install git -y
RUN yum install maven -y
CMD [ "nginx", "-g", "daemon off;" ]