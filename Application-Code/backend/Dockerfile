FROM public.ecr.aws/docker/library/node:14
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
CMD ["node", "index.js"]
