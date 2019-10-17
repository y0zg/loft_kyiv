FROM node:12-alpine		

EXPOSE 3000		

ADD . /app			
WORKDIR app	

RUN npm install	
CMD ["node", "app.js"]