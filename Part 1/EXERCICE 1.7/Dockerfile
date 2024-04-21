FROM ubuntu:22.04

WORKDIR /app
COPY script.sh .

RUN apt update && apt -y upgrade \
    && apt -y install curl \
    && chmod +x script.sh

CMD ["./script.sh"]