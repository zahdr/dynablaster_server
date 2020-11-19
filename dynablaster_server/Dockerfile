FROM ubuntu:18.04

RUN apt update -y
RUN apt install -y libqtgui4

RUN mkdir /dynablaster_server
WORKDIR /dynablaster_server
COPY app/server_linux_x64 /dynablaster_server/server_linux_x64

CMD ["./server_linux_x64"]