FROM --platform=linux/amd64 public.ecr.aws/lambda/nodejs:20

COPY app.js package*.json ./
RUN npm install

CMD [ "app.lambdaHandler" ]
