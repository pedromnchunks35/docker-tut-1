#SPECIFY THE PARENT IMAGE WHICH WILL BE A NODE ONE FROM DOCKER HUB
FROM node:17-alpine
#THE WORKDIR FOR WHERE YOU WILL COPY THE FILES AND WHERE YOU WILL RUN COMMANDS
WORKDIR /app
#FIRST "." MEANS THE FILES FROM THE DIRECTORY WHERE THIS DOCKER FILE IS , SECOUND MEANS THE DIR WHERE YOU WILL PASTE IN THE DOCKER CONTAINER
COPY . .
#INSTALL NODE DEPENDENCIES
RUN npm install
#PORT MAPPING
EXPOSE 4000
#COMMANDS TO RUN AFTER THE BUILD PHASE
CMD ["node", "app.js"]
