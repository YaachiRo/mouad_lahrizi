# download ubuntu image from docker registery
# docker registery is like a store for already built image


FROM ubuntu:oracular


# construct image with latest package updates and indexes from apt
RUN apt update -y && apt upgrade -y

# install useful packages
RUN apt install build-essential git curl -y


# cd /data 
WORKDIR /data
# dont use cmd if tty true in docker compose file

# CMD ["bash"]