FROM node:18
WORKDIR /usr/src/app/frontend
COPY . .
RUN ["npm" ,"install"]
EXPOSE 3008
CMD ["npm", "run", "serve"]
