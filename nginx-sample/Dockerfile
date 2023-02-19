FROM nginx:latest
WORKDIR /nginx-sample
COPY nginx.conf /etc/nginx/conf.d/default.conf
COPY package*.json ./
COPY . .
EXPOSE 3000
