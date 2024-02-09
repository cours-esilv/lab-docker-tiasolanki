FROM nginx:latest

COPY . /usr/share/nginx/html

ENV WS_BACK_URL=http://5002:5000

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
