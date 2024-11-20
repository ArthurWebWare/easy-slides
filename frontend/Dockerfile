FROM node:18

WORKDIR /app

COPY package*.json ./
#RUN npm install || cat npm-debug.log

COPY . .

EXPOSE 5173

CMD ["npm", "install"]

#CMD ["tail", "-f", "/dev/null"]

CMD ["npm", "run", "dev", "--", "--host=0.0.0.0"]