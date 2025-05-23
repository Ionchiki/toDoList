#FROM nginx:alpine 
##FROM node:18-alpine as build 
#WORKDIR /app 
##COPY package.json ./ 
#COPY . . 
##RUN npm run build 



##RUN rm -rf /usr/share/nginx/html/* 
 
##COPY --from=build /app/dist /usr/share/nginx/html 
FROM nginx:alpine
WORKDIR /usr/share/nginx/html
COPY . .
EXPOSE 80