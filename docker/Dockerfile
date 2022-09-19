FROM nginx:alpine
RUN apk update && apk add bash
RUN apk add --update nodejs npm
RUN npm install -g @ionic/cli
WORKDIR /app/myapp



#após criar o projeto com ionic start
#npm install -g @angular/cli
#npm i @angular-devkit/build-angular