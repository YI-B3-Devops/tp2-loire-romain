FROM node:lts-alpine

ENV NODE_ENV development
ENV API_PORT 3000

# Create app directory
WORKDIR /home/node/app
RUN chown -R node:node /home/node/app
USER node

# Commands at runtime
# Command "dev" does not work
CMD [ "npm", "run", "start" ]