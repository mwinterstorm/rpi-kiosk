FROM balenalib/raspberrypi3-debian:buster
RUN sudo apt-get update && sudo apt-get install --no-install-recommends -y \
	openbox \
    xserver-xorg \
    xinit \
    xserver-xorg-video-fbdev

COPY x.sh /
CMD ["/x.sh"]