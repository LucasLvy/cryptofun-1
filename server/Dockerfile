FROM node:14.16.0

WORKDIR /app

EXPOSE 4000

# Copy source code from src to /app/src
COPY src src/

COPY .eslintrc.js package.json package-lock.json ./

RUN npm install

CMD ["npm", "run", "dev"]