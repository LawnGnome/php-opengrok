FROM alpine

RUN apk update && apk add git
ADD git-new-workdir /usr/local/bin/
ADD clone /usr/local/bin/
ADD start /usr/local/bin/

CMD /usr/local/bin/start
