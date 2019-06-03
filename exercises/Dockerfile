FROM ubuntu

RUN apt update -y
RUN apt install curl -y

WORKDIR /usr/src

COPY script_ex1_5.sh /usr/src

CMD ["sh", "script_ex1_5.sh"]
