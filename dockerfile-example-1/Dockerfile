FROM alpine
MAINTAINER raghwendra <raghz1994@gmail.com>
RUN apk update && apk add nodejs
RUN mkdir average
ADD average.js average/
WORKDIR average
ENTRYPOINT ["node", "average.js"]

