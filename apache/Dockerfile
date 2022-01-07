FROM lyh/ubi:test
MAINTAINER young <_dldudgjs31@naver.com_>
LABEL description="A custom Apache container based on UBI 8"
RUN yum install -y httpd && \
yum clean all
RUN echo "Hello from Containerfile" > /var/www/html/index.html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]
