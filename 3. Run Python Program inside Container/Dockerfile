FROM ubuntu:18.04

ARG target_dir
ADD ${target_dir} /app

WORKDIR /app

RUN apt-get update && apt-get install -y python

CMD [ "python","sample.py" ]
