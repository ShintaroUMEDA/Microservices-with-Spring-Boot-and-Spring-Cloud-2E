FROM openjdk:8
RUN apt update && apt install -y jq
RUN useradd -m -d /home/dev-user -s /bin/bash dev-user
USER dev-user