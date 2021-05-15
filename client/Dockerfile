FROM node:12.17.0

LABEL version="1.0"
LABEL description="This is the base docker for client React App"
LABEL maintainer="tvthong1995@gmail.com"

WORKDIR /app

COPY ["package.json", "yarn.lock", "./"]

RUN yarn 

COPY . .

EXPOSE 3000 

CMD ["yarn", "start"]