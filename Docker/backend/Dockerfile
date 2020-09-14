FROM python:3.6
WORKDIR /src/app/server/static
# COPY package.json /src/app/server/static/package.json
ARG NODE_VERSION="8.x"
RUN curl -sL "https://deb.nodesource.com/setup_${NODE_VERSION}" | bash - \
 && apt-get install --no-install-recommends -y \
      nodejs
RUN apt install -y npm 
RUN npm install
