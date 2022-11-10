FROM python:3.6.9-alpine3.9
COPY src /src
WORKDIR /src
RUN pip3 install -r requirements.txt
ENV PATH="/src:{$PATH}"
ENTRYPOINT ["entrypoint.sh"]


 
