FROM almalinux:9
#CMD ["ping", "google.com"]
RUN dnf install git -y
RUN useradd sivakumar

USER sivakumar    # running the container with normal user sivakumar
CMD ["google.com"]
ENTRYPOINT ["ping"]
