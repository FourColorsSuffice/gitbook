FROM ubuntu
RUN apt-get update && \
    apt-get install -y \
            git \
            nodejs \
            npm
WORKDIR /app
RUN git clone \
    https://github.com/fourcolorssuffice/gitbook.git
RUN npm install
EXPOSE 8080
CMD ["npm", "start"]
