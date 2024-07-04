FROM node:18.16

WORKDIR /web/

RUN npm install -g @angular/cli@15.0.3

# Set environment variable to disable Google Analytics
ENV NG_CLI_ANALYTICS="false"

CMD bash -c "npm install && ng serve --host=0.0.0.0 --disable-host-check --poll=1000"
