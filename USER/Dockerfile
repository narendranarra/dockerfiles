FROM almalinux:9
#CMD ["ping", "google.com"]
RUN dnf install git -y
RUN useradd -m sivakumar

USER sivakumar    # running the container with normal user sivakumar
WORKDIR /home/sivakumar
CMD ["google.com"]
ENTRYPOINT ["ping"]
