FROM python:3.7-alpine3.16
RUN apk update && apk upgrade --no-cache
COPY src /src
WORKDIR /src
RUN pip3 install -r requirements.txt
ENV PATH="/src:{$PATH}"
ENTRYPOINT ["entrypoint.sh"]


 
