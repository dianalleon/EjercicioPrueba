FROM nginx

RUN mkdir -p /home/app

COPY . /home/app

EXPOSE 8080

CMD ["nginx", "/home/app/index.html"]
